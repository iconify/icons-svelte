<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/u/ufn3m0bhg.css';
import '../../css/r/r89a8rhhw.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/l/lcj2fov3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ufn3m0bhg wm-deco"/><path class="r89a8rhhw wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="lcj2fov3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-gift-blueprint" {...props}></Icon>
