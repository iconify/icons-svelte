<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa4-7mbfv.css';
import '../../css/p/piuz0fbpu.css';
import '../../css/k/k2hdxcbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pa4-7mbfv"/><path class="piuz0fbpu"/><path class="k2hdxcbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:casaos" {...props}></Icon>
