<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hukkl55px.css';
import '../../css/w/w4o_mqs1s.css';
import '../../css/a/a4drb_btg.css';
import '../../css/q/qe7bs-blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hukkl55px wm-a"/><path class="w4o_mqs1s wm-k"/><path class="a4drb_btg wm-a"/><path class="qe7bs-blu wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lunar-drum-sketch" {...props}></Icon>
