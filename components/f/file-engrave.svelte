<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u9-4l6bjs.css';
import '../../css/o/olh21jifq.css';
import '../../css/v/vp3_m3b5w.css';
import '../../css/z/z4bbp2bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u9-4l6bjs wm-k"/><path class="olh21jifq wm-shadow"/><path class="vp3_m3b5w wm-k"/><path class="wm-a z4bbp2bhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-engrave" {...props}></Icon>
