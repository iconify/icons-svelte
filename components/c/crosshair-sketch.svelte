<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lgreg-b0h.css';
import '../../css/t/tejekv0yd.css';
import '../../css/g/gp-44obuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lgreg-b0h wm-k"/><path class="tejekv0yd wm-k"/><path class="gp-44obuf wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crosshair-sketch" {...props}></Icon>
