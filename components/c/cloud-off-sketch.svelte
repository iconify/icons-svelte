<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qczcrlmsi.css';
import '../../css/e/eh9yg0bsm.css';
import '../../css/b/bxel2rbnc.css';
import '../../css/b/b1xdfvzax.css';
import '../../css/t/ts2ozy7et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qczcrlmsi"/><path class="eh9yg0bsm wm-k"/><path class="bxel2rbnc wm-s"/><path class="b1xdfvzax wm-k"/><path class="ts2ozy7et wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-off-sketch" {...props}></Icon>
