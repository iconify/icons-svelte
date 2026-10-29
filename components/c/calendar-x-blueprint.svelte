<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/fj43dsa4b.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/j/johjr7vlq.css';
import '../../css/h/hp_yrebrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="fj43dsa4b wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="johjr7vlq wm-k"/><path class="hp_yrebrn wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-x-blueprint" {...props}></Icon>
