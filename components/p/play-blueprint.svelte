<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/c1xpabbuz.css';
import '../../css/e/ey6g4zpde.css';
import '../../css/m/mdh1f_tph.css';
import '../../css/j/jzrgssbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="c1xpabbuz wm-deco"/><path class="ey6g4zpde wm-deco"/><path class="mdh1f_tph wm-deco"/><path class="jzrgssbeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:play-blueprint" {...props}></Icon>
