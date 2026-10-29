<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/h0x03r3ma.css';
import '../../css/x/xb52eebsk.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/o/onq_9wbtr.css';
import '../../css/q/qi8t6w18c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="h0x03r3ma wm-deco"/><path class="wm-deco xb52eebsk"/><path class="o7-ag87sb wm-deco"/><path class="onq_9wbtr wm-k"/><path class="qi8t6w18c wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:palette-blueprint" {...props}></Icon>
