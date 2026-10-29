<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/etzt8li8p.css';
import '../../css/l/lv9qmw66s.css';
import '../../css/q/q0mlcsbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="etzt8li8p wm-a"/><path class="lv9qmw66s wm-k"/><path class="q0mlcsbte wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-candlestick-sketch" {...props}></Icon>
