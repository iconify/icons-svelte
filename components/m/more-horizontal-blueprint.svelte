<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/nrlirxy2k.css';
import '../../css/c/cwfio2b2w.css';
import '../../css/g/gcatcbilq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="nrlirxy2k wm-deco"/><path class="cwfio2b2w wm-deco"/><path class="gcatcbilq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:more-horizontal-blueprint" {...props}></Icon>
