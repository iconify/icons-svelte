<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/u/us1q1oobo.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/p/p29y99yxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="us1q1oobo wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="p29y99yxr wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layout-grid-blueprint" {...props}></Icon>
