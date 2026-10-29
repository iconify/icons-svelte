<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tk223ccsq.css';
import '../../css/h/h7-01hbkm.css';
import '../../css/l/l24f3obhv.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/g/gwt5kac8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tk223ccsq wm-k"/><path class="h7-01hbkm wm-a"/><path class="l24f3obhv wm-shadow"/><path class="wm-k yw4fz_b6b"/><path class="gwt5kac8n wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:contrast-engrave" {...props}></Icon>
