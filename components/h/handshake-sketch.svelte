<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t3fmph07q.css';
import '../../css/z/zed8uz8yd.css';
import '../../css/e/exdiltbqb.css';
import '../../css/r/rjtu802pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t3fmph07q wm-k"/><path class="wm-a zed8uz8yd"/><path class="exdiltbqb wm-k"/><path class="rjtu802pw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:handshake-sketch" {...props}></Icon>
