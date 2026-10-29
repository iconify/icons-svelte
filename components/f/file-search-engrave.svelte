<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wwup1x10z.css';
import '../../css/g/gwmckxxys.css';
import '../../css/o/olh21jifq.css';
import '../../css/v/vp3_m3b5w.css';
import '../../css/a/alhx0z7iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k wwup1x10z"/><path class="gwmckxxys wm-a"/><path class="olh21jifq wm-shadow"/><path class="vp3_m3b5w wm-k"/><path class="alhx0z7iy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-search-engrave" {...props}></Icon>
