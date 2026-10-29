<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/s2fzgqp6w.css';
import '../../css/v/vke7uysby.css';
import '../../css/o/oorih5bvf.css';
import '../../css/x/xt8yg9bhd.css';
import '../../css/y/yw1d64mhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="s2fzgqp6w wm-deco"/><path class="vke7uysby wm-deco"/><path class="oorih5bvf wm-deco"/><path class="wm-k xt8yg9bhd"/><path class="wm-a yw1d64mhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bat-blueprint" {...props}></Icon>
