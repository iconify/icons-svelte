<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l5w8pibgw.css';
import '../../css/k/kn3v5rl7b.css';
import '../../css/h/hn6qrhojp.css';
import '../../css/d/di1d0ffeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l5w8pibgw"/><path class="kn3v5rl7b wm-k"/><path class="hn6qrhojp wm-k"/><path class="di1d0ffeq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mushroom-sketch" {...props}></Icon>
