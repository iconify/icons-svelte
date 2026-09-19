<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/inmr35bmm.css';
import '../../css/i/ij1h_i4xk.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsLactoseNegative0)" class="cuyn6tgcc"><path class="inmr35bmm"/><path clip-rule="evenodd" class="ij1h_i4xk"/></g><defs><clipPath id="healthiconsLactoseNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lactose-negative" {...props}></Icon>
