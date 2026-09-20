<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx-nx6b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qx-nx6b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-on-trailer-on-ramp-on-water" {...props}></Icon>
