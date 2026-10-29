<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m14e8zlyt.css';
import '../../css/c/c6tjo7bgx.css';
import '../../css/u/upi6evbrs.css';
import '../../css/m/mf6znbcws.css';
import '../../css/w/w3o0x094m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m14e8zlyt"/><path class="c6tjo7bgx wm-k"/><path class="upi6evbrs wm-a"/><path class="mf6znbcws wm-k"/><path class="w3o0x094m wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:refrigerator-sketch" {...props}></Icon>
