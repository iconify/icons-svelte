<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lx2k10m7m.css';
import '../../css/j/j6ucl9bbz.css';
import '../../css/o/o835chb2f.css';
import '../../css/b/bsjsm791p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lx2k10m7m wm-deco"/><path class="j6ucl9bbz wm-deco"/><path class="o835chb2f"/><path class="bsjsm791p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-down-blueprint" {...props}></Icon>
