<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qdf62dcxv.css';
import '../../css/w/whbsvqbtd.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthicons9Negative0)" class="cuyn6tgcc"><path class="qdf62dcxv"/><path clip-rule="evenodd" class="whbsvqbtd"/></g><defs><clipPath id="healthicons9Negative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:9-negative" {...props}></Icon>
