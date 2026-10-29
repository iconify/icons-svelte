<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lkonv1d3d.css';
import '../../css/g/gkxcr3bvl.css';
import '../../css/w/wi19j-lxz.css';
import '../../css/p/pz6n94bed.css';
import '../../css/j/jfnfrsbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lkonv1d3d wm-k"/><path class="gkxcr3bvl wm-k"/><path class="wi19j-lxz wm-k"/><path class="pz6n94bed wm-a"/><path class="jfnfrsbiy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:alert-circle-sketch" {...props}></Icon>
