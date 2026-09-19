<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ozol2rd-l.css';
import '../../css/k/knjrpsbqf.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsRNegative0)" class="cuyn6tgcc"><path class="ozol2rd-l"/><path clip-rule="evenodd" class="knjrpsbqf"/></g><defs><clipPath id="healthiconsRNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:r-negative" {...props}></Icon>
