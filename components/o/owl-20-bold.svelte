<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2w_usb8e.css';
import '../../css/p/p0fmtdpyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t2w_usb8e"/><path class="p0fmtdpyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:owl-20-bold" {...props}></Icon>
