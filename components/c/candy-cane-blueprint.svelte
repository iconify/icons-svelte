<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gv-ry10ad.css';
import '../../css/k/kvsm9yfir.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/t/taffm8blt.css';
import '../../css/u/uya6wcbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gv-ry10ad wm-deco"/><path class="kvsm9yfir wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="taffm8blt wm-k"/><path class="uya6wcbfz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:candy-cane-blueprint" {...props}></Icon>
