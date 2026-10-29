<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cn1x6iioy.css';
import '../../css/r/rou8wpb_j.css';
import '../../css/r/rhxxk9bkj.css';
import '../../css/b/bt--9eb0w.css';
import '../../css/h/hqgq3dbge.css';
import '../../css/h/hpi0ccblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cn1x6iioy wm-k"/><path class="rou8wpb_j wm-a"/><path class="rhxxk9bkj wm-shadow"/><path class="bt--9eb0w wm-a"/><path class="hqgq3dbge wm-k"/><path class="hpi0ccblh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plug-engrave" {...props}></Icon>
