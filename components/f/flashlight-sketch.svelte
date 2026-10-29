<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d8_t8lbuc.css';
import '../../css/z/ztqy_vbrk.css';
import '../../css/n/ni4t_eb3e.css';
import '../../css/v/vokqhtb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d8_t8lbuc"/><path class="wm-k ztqy_vbrk"/><path class="ni4t_eb3e wm-a"/><path class="vokqhtb2z wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flashlight-sketch" {...props}></Icon>
