<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/ui-h4lkhg.css';
import '../../css/d/dmrwy4buz.css';
import '../../css/h/hwksmab1d.css';
import '../../css/m/mclry9-jv.css';
import '../../css/d/djj1_0nws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ui-h4lkhg"/><path class="dmrwy4buz wm-k"/><path class="hwksmab1d wm-k"/><path class="mclry9-jv wm-a"/><path class="djj1_0nws wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-gantt-sketch" {...props}></Icon>
