<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sg_r1w5zy.css';
import '../../css/h/hl1483cic.css';
import '../../css/e/ejyojtvpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="sg_r1w5zy"/><path class="hl1483cic"/><path clip-rule="evenodd" class="ejyojtvpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:i-schedule-school-date-time" {...props}></Icon>
