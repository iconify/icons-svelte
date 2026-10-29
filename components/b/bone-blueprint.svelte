<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/w/wt_palbew.css';
import '../../css/o/o7f98jbya.css';
import '../../css/r/r65vtx55l.css';
import '../../css/v/vbhvu6boy.css';
import '../../css/x/xsvsuubze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco wt_palbew"/><path class="o7f98jbya wm-deco"/><path class="r65vtx55l wm-deco"/><path class="vbhvu6boy"/><path class="xsvsuubze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bone-blueprint" {...props}></Icon>
