<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w6n12bf4c.css';
import '../../css/m/mofnaebna.css';
import '../../css/g/g2gi1nbsb.css';
import '../../css/r/rds1m8b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w6n12bf4c"/><path class="mofnaebna wm-a"/><path class="g2gi1nbsb wm-k"/><path class="rds1m8b5p wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:brain-circuit-sketch" {...props}></Icon>
