<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/ic6c7lb6f.css';
import '../../css/r/r5g8grb6p.css';
import '../../css/d/dlmywhbph.css';
import '../../css/k/kpi72jrye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ic6c7lb6f wm-deco"/><path class="r5g8grb6p wm-deco"/><path class="dlmywhbph wm-deco"/><path class="kpi72jrye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fireplace-blueprint" {...props}></Icon>
