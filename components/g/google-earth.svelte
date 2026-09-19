<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4k4ixbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="b4k4ixbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:google-earth" {...props}></Icon>
