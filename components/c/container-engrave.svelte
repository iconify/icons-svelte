<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/doky59b1a.css';
import '../../css/d/dskoxmboo.css';
import '../../css/g/gc_-hub4z.css';
import '../../css/t/tsqe1pboz.css';
import '../../css/l/lq23_x48i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="doky59b1a wm-k"/><path class="dskoxmboo wm-shadow"/><path class="gc_-hub4z wm-k"/><path class="tsqe1pboz wm-k"/><path class="lq23_x48i wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:container-engrave" {...props}></Icon>
