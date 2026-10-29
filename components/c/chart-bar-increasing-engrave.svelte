<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u4654lkvf.css';
import '../../css/x/xgxrfebxf.css';
import '../../css/t/t53o8mnme.css';
import '../../css/s/skn8acc-z.css';
import '../../css/r/ralcq11vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u4654lkvf wm-k"/><path class="wm-a xgxrfebxf"/><path class="t53o8mnme wm-shadow"/><path class="skn8acc-z wm-a"/><path class="ralcq11vz wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-bar-increasing-engrave" {...props}></Icon>
