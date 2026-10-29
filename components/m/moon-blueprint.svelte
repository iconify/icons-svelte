<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gbfj4eb-n.css';
import '../../css/o/otfr25bmf.css';
import '../../css/p/pad0p8bhg.css';
import '../../css/w/wt9elgabp.css';
import '../../css/z/z29ur_b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gbfj4eb-n wm-deco"/><path class="otfr25bmf wm-deco"/><path class="pad0p8bhg wm-deco"/><path class="wt9elgabp"/><path class="z29ur_b7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:moon-blueprint" {...props}></Icon>
