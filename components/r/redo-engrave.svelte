<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tpn35eb9n.css';
import '../../css/b/bryy_6b1h.css';
import '../../css/w/w3_tn0w_p.css';
import '../../css/r/rwcpvtbgb.css';
import '../../css/l/lb1a6hbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tpn35eb9n wm-k"/><path class="bryy_6b1h wm-a"/><path class="w3_tn0w_p wm-shadow"/><path class="rwcpvtbgb wm-k"/><path class="lb1a6hbix wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:redo-engrave" {...props}></Icon>
