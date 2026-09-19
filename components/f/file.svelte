<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2ew5t0wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="j2ew5t0wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:file" {...props}></Icon>
