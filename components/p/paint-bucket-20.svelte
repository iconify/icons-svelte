<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzzrqibpu.css';
import '../../css/i/ilum5ccux.css';
import '../../css/r/rtzhn3bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tzzrqibpu"/><path class="ilum5ccux"/><path class="rtzhn3bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paint-bucket-20" {...props}></Icon>
