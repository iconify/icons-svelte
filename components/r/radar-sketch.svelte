<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ia2gzct5r.css';
import '../../css/n/nd9pb_bwa.css';
import '../../css/k/kd08ygb7j.css';
import '../../css/t/t0oo84s0x.css';
import '../../css/q/qcidxubyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ia2gzct5r wm-a"/><path class="nd9pb_bwa wm-k"/><path class="kd08ygb7j wm-k"/><path class="t0oo84s0x wm-a"/><path class="qcidxubyu wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:radar-sketch" {...props}></Icon>
