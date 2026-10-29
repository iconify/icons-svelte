<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/me6hq05dp.css';
import '../../css/h/hzh35zb_u.css';
import '../../css/d/df-t2ybaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="me6hq05dp"/><path class="hzh35zb_u wm-k"/><path class="df-t2ybaq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bee-sketch" {...props}></Icon>
