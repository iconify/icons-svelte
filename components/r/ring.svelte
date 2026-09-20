<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0-jx1bpp.css';
import '../../css/k/kx_1d-sfu.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/x/xecxklbhv.css';
import '../../css/x/xfdyl25bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="a0-jx1bpp"/><path class="kx_1d-sfu"/><g class="ij2x_72vy"><circle class="xecxklbhv"/><path class="xfdyl25bs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ring" {...props}></Icon>
