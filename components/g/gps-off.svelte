<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlb99pbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="rlb99pbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:gps-off" {...props}></Icon>
