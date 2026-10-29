<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ez05224-i.css';
import '../../css/w/wciayxbdl.css';
import '../../css/l/llxyupbek.css';
import '../../css/f/fnr8gob4l.css';
import '../../css/n/nsiaxmbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ez05224-i"/><path class="wciayxbdl wm-k"/><path class="llxyupbek wm-a"/><path class="fnr8gob4l wm-k"/><path class="nsiaxmbcn wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-code-sketch" {...props}></Icon>
