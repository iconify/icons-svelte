<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m19lpcb0d.css';
import '../../css/t/tf6q4k9qf.css';
import '../../css/p/puozkrmyl.css';
import '../../css/u/urb3kpbld.css';
import '../../css/i/idk2wtbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m19lpcb0d wm-k"/><path class="tf6q4k9qf wm-a"/><path class="puozkrmyl wm-shadow"/><path class="urb3kpbld wm-k"/><path class="idk2wtbbi wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:droplets-engrave" {...props}></Icon>
