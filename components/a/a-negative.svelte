<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w-j95hfmm.css';
import '../../css/y/yhrwsxnxg.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsANegative0)" class="cuyn6tgcc"><path class="w-j95hfmm"/><path clip-rule="evenodd" class="yhrwsxnxg"/></g><defs><clipPath id="healthiconsANegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:a-negative" {...props}></Icon>
