<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/we01h7bqs.css';
import '../../css/k/kumc9-wvn.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsCastNegative0)" class="cuyn6tgcc"><path class="we01h7bqs"/><path clip-rule="evenodd" class="kumc9-wvn"/></g><defs><clipPath id="healthiconsCastNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cast-negative" {...props}></Icon>
