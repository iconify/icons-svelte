<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lzik7ibny.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/j/johjr7vlq.css';
import '../../css/x/xxfl8ubmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lzik7ibny wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="johjr7vlq wm-k"/><path class="wm-a xxfl8ubmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-heart-blueprint" {...props}></Icon>
