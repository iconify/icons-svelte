<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gr9r66bcx.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/c/cbppcqbmj.css';
import '../../css/y/ybp_pqrii.css';
import '../../css/l/lsgotya9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gr9r66bcx wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="cbppcqbmj wm-k"/><path class="wm-a ybp_pqrii"/><path class="lsgotya9q wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:audio-lines-blueprint" {...props}></Icon>
