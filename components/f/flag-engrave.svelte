<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/ybnlb-4lm.css';
import '../../css/o/ooiyb2s2v.css';
import '../../css/e/eo1aulits.css';
import '../../css/z/zbms0lbwh.css';
import '../../css/v/vs3_2yq5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k ybnlb-4lm"/><path class="ooiyb2s2v wm-a"/><path class="eo1aulits wm-shadow"/><path class="wm-k zbms0lbwh"/><path class="vs3_2yq5q wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flag-engrave" {...props}></Icon>
