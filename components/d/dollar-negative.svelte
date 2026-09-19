<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u1xqpmbgn.css';
import '../../css/b/b99qn9rzk.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsDollarNegative0)" class="cuyn6tgcc"><path class="u1xqpmbgn"/><path clip-rule="evenodd" class="b99qn9rzk"/></g><defs><clipPath id="healthiconsDollarNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dollar-negative" {...props}></Icon>
