<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vljw1kbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":504,"height":440};
const content = `<path class="vljw1kbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:network-wifi-off" {...props}></Icon>
