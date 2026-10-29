<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qjgdbowmx.css';
import '../../css/g/gvws9nb5q.css';
import '../../css/o/oxv1zccrk.css';
import '../../css/o/owa8_zbgh.css';
import '../../css/q/q2bjfsbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qjgdbowmx wm-k"/><path class="gvws9nb5q wm-a"/><path class="oxv1zccrk wm-k"/><path class="owa8_zbgh wm-a"/><path class="q2bjfsbys wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:christmas-candle-sketch" {...props}></Icon>
