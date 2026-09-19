<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmxl5mk7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="xmxl5mk7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:google-plus" {...props}></Icon>
