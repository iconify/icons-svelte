<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/ncjp18bwi.css';
import '../../css/z/zhjby8xue.css';
import '../../css/v/vs77whb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ncjp18bwi wm-deco"/><path class="wm-deco zhjby8xue"/><path class="vs77whb3h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:infinity-blueprint" {...props}></Icon>
