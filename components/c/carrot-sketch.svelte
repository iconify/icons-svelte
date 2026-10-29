<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/swjw8utmb.css';
import '../../css/i/i-q4x88yc.css';
import '../../css/d/d6q4sp3-o.css';
import '../../css/z/zaja4-btu.css';
import '../../css/w/w38foqb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="swjw8utmb"/><path class="i-q4x88yc wm-k"/><path class="d6q4sp3-o wm-a"/><path class="wm-k zaja4-btu"/><path class="w38foqb-l wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:carrot-sketch" {...props}></Icon>
