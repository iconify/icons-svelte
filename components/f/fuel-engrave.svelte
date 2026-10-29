<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vbedhib0q.css';
import '../../css/e/ep3o2ubpc.css';
import '../../css/x/xy3kxv0cu.css';
import '../../css/v/vlroo4bwv.css';
import '../../css/k/kjftorklk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vbedhib0q wm-k"/><path class="ep3o2ubpc wm-a"/><path class="wm-shadow xy3kxv0cu"/><path class="vlroo4bwv wm-k"/><path class="kjftorklk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fuel-engrave" {...props}></Icon>
