<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rcffozb7g.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsChartLineNegative0)"><path clip-rule="evenodd" class="rcffozb7g"/></g><defs><clipPath id="healthiconsChartLineNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-line-negative" {...props}></Icon>
