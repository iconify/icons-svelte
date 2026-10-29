<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/r8szkwwde.css';
import '../../css/a/ag6daps-l.css';
import '../../css/b/bxjv56brc.css';
import '../../css/j/jura4nbok.css';
import '../../css/f/fcpcu9i2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="r8szkwwde wm-deco"/><path class="ag6daps-l wm-deco"/><path class="bxjv56brc wm-deco"/><path class="jura4nbok wm-k"/><path class="fcpcu9i2b wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:magnet-blueprint" {...props}></Icon>
