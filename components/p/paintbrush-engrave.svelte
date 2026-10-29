<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pzh4jacwq.css';
import '../../css/f/fey6353zj.css';
import '../../css/z/zlwfcob2u.css';
import '../../css/x/xr7tqnbdl.css';
import '../../css/z/zkgki1b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pzh4jacwq wm-k"/><path class="fey6353zj wm-a"/><path class="wm-shadow zlwfcob2u"/><path class="wm-k xr7tqnbdl"/><path class="wm-k zkgki1b_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paintbrush-engrave" {...props}></Icon>
