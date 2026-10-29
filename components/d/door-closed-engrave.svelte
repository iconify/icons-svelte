<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hpu2ghv2w.css';
import '../../css/w/w1zs2bbif.css';
import '../../css/i/ic5g_yble.css';
import '../../css/s/smls78shz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hpu2ghv2w wm-k"/><path class="w1zs2bbif wm-shadow"/><path class="ic5g_yble wm-k"/><path class="smls78shz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:door-closed-engrave" {...props}></Icon>
