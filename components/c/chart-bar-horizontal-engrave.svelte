<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zkoj08ryw.css';
import '../../css/x/xgxrfebxf.css';
import '../../css/j/jjih60n0t.css';
import '../../css/s/skn8acc-z.css';
import '../../css/s/sjsppzltu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k zkoj08ryw"/><path class="wm-a xgxrfebxf"/><path class="jjih60n0t wm-shadow"/><path class="skn8acc-z wm-a"/><path class="sjsppzltu wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-bar-horizontal-engrave" {...props}></Icon>
