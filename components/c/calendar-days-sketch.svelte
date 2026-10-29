<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y1asmybzv.css';
import '../../css/j/jt0ne9b_u.css';
import '../../css/v/vug_eabcd.css';
import '../../css/f/f7unpibui.css';
import '../../css/j/j_h2px3hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y1asmybzv"/><path class="jt0ne9b_u wm-k"/><path class="vug_eabcd wm-a"/><path class="f7unpibui wm-k"/><path class="j_h2px3hc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-days-sketch" {...props}></Icon>
