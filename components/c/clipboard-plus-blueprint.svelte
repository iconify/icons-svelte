<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/nxcru783l.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/m/mzsw-jb7t.css';
import '../../css/n/nk903fbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="nxcru783l wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="mzsw-jb7t wm-k"/><path class="nk903fbll wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clipboard-plus-blueprint" {...props}></Icon>
