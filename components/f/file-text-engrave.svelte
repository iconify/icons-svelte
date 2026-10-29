<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b7l65nb-a.css';
import '../../css/g/gwmckxxys.css';
import '../../css/o/olh21jifq.css';
import '../../css/v/vp3_m3b5w.css';
import '../../css/b/btwv_isko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b7l65nb-a wm-k"/><path class="gwmckxxys wm-a"/><path class="olh21jifq wm-shadow"/><path class="vp3_m3b5w wm-k"/><path class="btwv_isko wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-text-engrave" {...props}></Icon>
