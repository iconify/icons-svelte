<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byoy_2dlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="byoy_2dlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-download-button-2-arrow-bottom-down-download-internet-network-server-upload" {...props}></Icon>
