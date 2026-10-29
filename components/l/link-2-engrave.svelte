<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x8enjjbsq.css';
import '../../css/x/xvcz328vn.css';
import '../../css/p/p3hd9ubtl.css';
import '../../css/o/ov_robb3s.css';
import '../../css/y/y875pzbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k x8enjjbsq"/><path class="wm-a xvcz328vn"/><path class="p3hd9ubtl wm-shadow"/><path class="ov_robb3s wm-k"/><path class="wm-a y875pzbpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:link-2-engrave" {...props}></Icon>
