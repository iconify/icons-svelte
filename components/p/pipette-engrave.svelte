<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e51_17bqm.css';
import '../../css/y/y971-sbup.css';
import '../../css/s/smlm6-8mf.css';
import '../../css/k/kcbeidzug.css';
import '../../css/t/t_jrdsb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e51_17bqm wm-k"/><path class="wm-a y971-sbup"/><path class="smlm6-8mf wm-shadow"/><path class="kcbeidzug wm-k"/><path class="t_jrdsb4n wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pipette-engrave" {...props}></Icon>
