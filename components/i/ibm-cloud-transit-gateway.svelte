<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm3ejky-b.css';
import '../../css/p/pe7z2bb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mm3ejky-b"/><path class="pe7z2bb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-transit-gateway" {...props}></Icon>
