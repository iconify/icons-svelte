<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/zjxf0acmm.css';
import '../../css/l/lu1ane3la.css';
import '../../css/s/sfhccvmst.css';
import '../../css/c/c5-x4cbou.css';
import '../../css/v/vxyac5iur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco zjxf0acmm"/><path class="lu1ane3la wm-deco"/><path class="sfhccvmst wm-deco"/><path class="c5-x4cbou wm-k"/><path class="vxyac5iur wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:banana-blueprint" {...props}></Icon>
