<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wrzg7sb4i.css';
import '../../css/j/j7rx7-6xl.css';
import '../../css/m/muiqo2blt.css';
import '../../css/n/n0z0dgety.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wrzg7sb4i"/><path class="j7rx7-6xl wm-a"/><path class="muiqo2blt wm-k"/><path class="n0z0dgety wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:copy-check-sketch" {...props}></Icon>
