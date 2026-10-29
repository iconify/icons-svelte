<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/brye_nbes.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/z/zvszdccwg.css';
import '../../css/n/ngurz8bhm.css';
import '../../css/d/dgp8ihnse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="brye_nbes wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="wm-k zvszdccwg"/><path class="ngurz8bhm wm-a"/><path class="dgp8ihnse wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:move-blueprint" {...props}></Icon>
