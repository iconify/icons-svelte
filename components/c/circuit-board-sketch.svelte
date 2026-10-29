<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p02usd09d.css';
import '../../css/d/di-npsbsf.css';
import '../../css/e/e9s7nacvv.css';
import '../../css/y/ydrhx_bvj.css';
import '../../css/x/xl0su_7tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p02usd09d"/><path class="di-npsbsf wm-k"/><path class="e9s7nacvv wm-k"/><path class="wm-a ydrhx_bvj"/><path class="wm-a xl0su_7tq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circuit-board-sketch" {...props}></Icon>
