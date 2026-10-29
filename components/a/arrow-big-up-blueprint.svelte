<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/dwbio1b7i.css';
import '../../css/e/ezxvi_nvu.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/k/kvozr-b3p.css';
import '../../css/j/jpij_nbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="dwbio1b7i wm-deco"/><path class="ezxvi_nvu wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="kvozr-b3p"/><path class="jpij_nbji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-big-up-blueprint" {...props}></Icon>
