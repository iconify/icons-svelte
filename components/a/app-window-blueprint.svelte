<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/yhaiccbkb.css';
import '../../css/g/g2xclxbug.css';
import '../../css/e/e_vgx2bxs.css';
import '../../css/g/g136touho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco yhaiccbkb"/><path class="g2xclxbug wm-deco"/><path class="e_vgx2bxs wm-k"/><path class="g136touho wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:app-window-blueprint" {...props}></Icon>
