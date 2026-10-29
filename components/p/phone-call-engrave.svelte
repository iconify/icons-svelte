<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tlsu4zyio.css';
import '../../css/z/z5q4-p_io.css';
import '../../css/e/e2gunbbka.css';
import '../../css/s/spnf93r-f.css';
import '../../css/q/qg-givbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tlsu4zyio wm-k"/><path class="wm-s z5q4-p_io"/><path class="e2gunbbka wm-shadow"/><path class="spnf93r-f wm-k"/><path class="qg-givbyo wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone-call-engrave" {...props}></Icon>
