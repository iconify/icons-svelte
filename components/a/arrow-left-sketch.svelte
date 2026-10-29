<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/irha4wb9h.css';
import '../../css/u/uch2m0oxc.css';
import '../../css/m/mslj97efm.css';
import '../../css/q/q7fzkwb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="irha4wb9h wm-k"/><path class="uch2m0oxc wm-a"/><path class="mslj97efm wm-k"/><path class="q7fzkwb4t wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-left-sketch" {...props}></Icon>
