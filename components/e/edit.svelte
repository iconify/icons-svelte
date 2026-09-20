<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpb2wnqoi.css';
import '../../css/h/hghm4ubpk.css';
import '../../css/n/ncr0rib2u.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/i/i-k--m3cg.css';
import '../../css/h/hx3n1ybjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lpb2wnqoi"/><path class="hghm4ubpk"/><path class="ncr0rib2u"/><g class="ij2x_72vy"><path class="i-k--m3cg"/><path class="hx3n1ybjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:edit" {...props}></Icon>
