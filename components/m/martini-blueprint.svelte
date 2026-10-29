<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/sbi0pnbbr.css';
import '../../css/g/gfet84u9u.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/d/dl4uzpqwq.css';
import '../../css/d/dhqc4ebed.css';
import '../../css/m/mqqas-bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="sbi0pnbbr wm-deco"/><path class="gfet84u9u wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="dl4uzpqwq wm-k"/><path class="dhqc4ebed wm-a"/><path class="mqqas-bsr wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:martini-blueprint" {...props}></Icon>
