<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xu_ouqb1p.css';
import '../../css/g/g9a4gtryo.css';
import '../../css/j/jstsvibwd.css';
import '../../css/n/n8lapqogo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xu_ouqb1p"/><path class="g9a4gtryo wm-shadow"/><path class="jstsvibwd wm-k"/><path class="n8lapqogo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dumpling-engrave" {...props}></Icon>
