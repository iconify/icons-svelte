<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd4o3lbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="rd4o3lbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:outlook" {...props}></Icon>
