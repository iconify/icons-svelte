<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/zbwom4blx.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/j/johjr7vlq.css';
import '../../css/a/a5cby0b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco zbwom4blx"/><path class="cf3uzcrzx wm-deco"/><path class="johjr7vlq wm-k"/><path class="a5cby0b9e wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-check-blueprint" {...props}></Icon>
