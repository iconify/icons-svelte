<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gg_n6i7ad.css';
import '../../css/b/b1dx1_bya.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsIDocumentsDeniedNegative0)" class="cuyn6tgcc"><path class="gg_n6i7ad"/><path clip-rule="evenodd" class="b1dx1_bya"/></g><defs><clipPath id="healthiconsIDocumentsDeniedNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:i-documents-denied-negative" {...props}></Icon>
