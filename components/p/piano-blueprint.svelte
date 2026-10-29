<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lu645yb-f.css';
import '../../css/g/g2xclxbug.css';
import '../../css/o/o7j3up99f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lu645yb-f wm-deco"/><path class="g2xclxbug wm-deco"/><path class="o7j3up99f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:piano-blueprint" {...props}></Icon>
