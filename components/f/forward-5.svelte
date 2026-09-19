<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2s2ztbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="p2s2ztbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:forward-5" {...props}></Icon>
