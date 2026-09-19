<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gp99vgb8b.css';
import '../../css/o/omghh6sin.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsQNegative0)" class="cuyn6tgcc"><path class="gp99vgb8b"/><path clip-rule="evenodd" class="omghh6sin"/></g><defs><clipPath id="healthiconsQNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:q-negative" {...props}></Icon>
