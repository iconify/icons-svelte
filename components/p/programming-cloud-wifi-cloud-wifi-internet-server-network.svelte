<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjymg8btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cjymg8btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:programming-cloud-wifi-cloud-wifi-internet-server-network" {...props}></Icon>
