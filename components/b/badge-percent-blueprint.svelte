<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/j7gwv8bmj.css';
import '../../css/j/jqr8ne24y.css';
import '../../css/r/r2fnfdpvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="j7gwv8bmj wm-deco"/><path class="jqr8ne24y wm-k"/><path class="r2fnfdpvh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:badge-percent-blueprint" {...props}></Icon>
