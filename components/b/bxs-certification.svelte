<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apy7cbb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apy7cbb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-certification" {...props}></Icon>
