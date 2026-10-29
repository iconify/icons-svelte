<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xik7p6btk.css';
import '../../css/c/co9hdudcl.css';
import '../../css/e/e7ssibbmt.css';
import '../../css/u/uh01hzbyb.css';
import '../../css/a/abeza2b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xik7p6btk"/><path class="co9hdudcl wm-a"/><path class="e7ssibbmt wm-shadow"/><path class="uh01hzbyb wm-k"/><path class="abeza2b1z wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-crack-engrave" {...props}></Icon>
