<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sieahlmzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sieahlmzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-upload-button-2-arrow-bottom-download-internet-network-erver-up-upload" {...props}></Icon>
