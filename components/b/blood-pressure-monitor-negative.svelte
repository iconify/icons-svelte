<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xthpdjbly.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsBloodPressureMonitorNegative0)"><path clip-rule="evenodd" class="xthpdjbly"/></g><defs><clipPath id="healthiconsBloodPressureMonitorNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-pressure-monitor-negative" {...props}></Icon>
