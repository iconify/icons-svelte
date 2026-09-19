<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xaaiztg2y.css';
import '../../css/b/byn2f-bjt.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsContactLensesNegative0)" class="cuyn6tgcc"><path class="xaaiztg2y"/><path clip-rule="evenodd" class="byn2f-bjt"/></g><defs><clipPath id="healthiconsContactLensesNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contact-lenses-negative" {...props}></Icon>
