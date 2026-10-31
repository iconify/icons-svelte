<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8zbr021d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8zbr021d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-info-fill-round" {...props}></Icon>
