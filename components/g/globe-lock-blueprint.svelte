<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/azgjlne8a.css';
import '../../css/r/ruwbbnbtn.css';
import '../../css/u/ukjvipc-p.css';
import '../../css/o/o9u4dqbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="azgjlne8a wm-deco"/><path class="ruwbbnbtn wm-deco"/><path class="ukjvipc-p wm-deco"/><path class="o9u4dqbcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:globe-lock-blueprint" {...props}></Icon>
