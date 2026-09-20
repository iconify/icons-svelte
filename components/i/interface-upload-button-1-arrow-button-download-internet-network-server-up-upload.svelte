<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjnkxhlvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jjnkxhlvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-upload-button-1-arrow-button-download-internet-network-server-up-upload" {...props}></Icon>
