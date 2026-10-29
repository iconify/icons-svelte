<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/db9oi35bt.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/b/bk5sigzvt.css';
import '../../css/e/exdxo5cyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="db9oi35bt wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="bk5sigzvt wm-k"/><path class="exdxo5cyc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:donut-blueprint" {...props}></Icon>
