<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fvkw4oiyc.css';
import '../../css/v/v5l5vgbks.css';
import '../../css/k/knx1hwb4l.css';
import '../../css/e/e_un4ubpg.css';
import '../../css/x/xkvin1h0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fvkw4oiyc"/><path class="v5l5vgbks"/><path class="knx1hwb4l"/><path class="e_un4ubpg"/><path class="xkvin1h0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gamepad-old-broken" {...props}></Icon>
