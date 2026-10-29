<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aalmtx25p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aalmtx25p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:filter" {...props}></Icon>
