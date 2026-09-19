<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xnhozabus.css';
import '../../css/y/yhq5o5b3n.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsPancreasNegative0)" class="cuyn6tgcc"><path class="xnhozabus"/><path clip-rule="evenodd" class="yhq5o5b3n"/></g><defs><clipPath id="healthiconsPancreasNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pancreas-negative" {...props}></Icon>
