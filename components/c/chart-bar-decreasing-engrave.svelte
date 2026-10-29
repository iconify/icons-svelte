<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/enheowbon.css';
import '../../css/x/xgxrfebxf.css';
import '../../css/v/vfndyme9l.css';
import '../../css/s/skn8acc-z.css';
import '../../css/c/c0bw40ovn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="enheowbon wm-k"/><path class="wm-a xgxrfebxf"/><path class="vfndyme9l wm-shadow"/><path class="skn8acc-z wm-a"/><path class="c0bw40ovn wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-bar-decreasing-engrave" {...props}></Icon>
