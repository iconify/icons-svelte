<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/bxl18ejyf.css';
import '../../css/w/wn-115bic.css';
import '../../css/k/kty6k6b5v.css';
import '../../css/d/dj8foab4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="bxl18ejyf wm-deco"/><path class="wm-deco wn-115bic"/><path class="kty6k6b5v"/><path class="dj8foab4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:menu-blueprint" {...props}></Icon>
