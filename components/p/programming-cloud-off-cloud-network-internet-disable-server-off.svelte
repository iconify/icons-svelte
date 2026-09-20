<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s034ffble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s034ffble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:programming-cloud-off-cloud-network-internet-disable-server-off" {...props}></Icon>
