<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gtmmvyb0k.css';
import '../../css/p/pkxbihy8h.css';
import '../../css/u/uzn2ehbxw.css';
import '../../css/l/lg-8n1num.css';
import '../../css/j/jsyt9abxh.css';
import '../../css/q/qpzat4bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gtmmvyb0k wm-k"/><path class="pkxbihy8h wm-a"/><path class="uzn2ehbxw wm-shadow"/><path class="lg-8n1num wm-k"/><path class="jsyt9abxh wm-a"/><path class="qpzat4bis wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circuit-board-engrave" {...props}></Icon>
