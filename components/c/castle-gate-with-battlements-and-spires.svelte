<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz42h1bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wz42h1bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:castle-gate-with-battlements-and-spires" {...props}></Icon>
