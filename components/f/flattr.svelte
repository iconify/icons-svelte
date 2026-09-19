<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-11k4bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="w-11k4bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flattr" {...props}></Icon>
