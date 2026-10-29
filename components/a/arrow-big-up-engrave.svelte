<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q4an57b1a.css';
import '../../css/m/mpw01vvnx.css';
import '../../css/h/hv_jolb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q4an57b1a"/><path class="mpw01vvnx wm-shadow"/><path class="hv_jolb_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-big-up-engrave" {...props}></Icon>
