<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osd8-xbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="osd8-xbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:camera-bw" {...props}></Icon>
