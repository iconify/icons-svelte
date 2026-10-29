<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t2vdistiz.css';
import '../../css/k/k3qcgxbnp.css';
import '../../css/b/buxga7syi.css';
import '../../css/z/zm38tmb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t2vdistiz wm-k"/><path class="k3qcgxbnp wm-shadow"/><path class="buxga7syi wm-k"/><path class="wm-a zm38tmb2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:passport-engrave" {...props}></Icon>
