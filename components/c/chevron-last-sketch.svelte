<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mi6_62o3d.css';
import '../../css/u/u_ak17bik.css';
import '../../css/v/vcd_rabzn.css';
import '../../css/f/f88le3b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mi6_62o3d wm-k"/><path class="u_ak17bik wm-k"/><path class="vcd_rabzn wm-a"/><path class="f88le3b-k wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-last-sketch" {...props}></Icon>
