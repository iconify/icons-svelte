<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/koiop_bgs.css';
import '../../css/t/t3pn7oyuv.css';
import '../../css/x/x7_2omoef.css';
import '../../css/m/mjecvc15l.css';
import '../../css/g/gfqmenbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="koiop_bgs wm-k"/><path class="t3pn7oyuv wm-a"/><path class="wm-shadow x7_2omoef"/><path class="mjecvc15l wm-k"/><path class="gfqmenbgk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:axe-engrave" {...props}></Icon>
