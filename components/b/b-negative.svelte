<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s0t-r4ksv.css';
import '../../css/x/xfnr5zbbb.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsBNegative0)" class="cuyn6tgcc"><path class="s0t-r4ksv"/><path clip-rule="evenodd" class="xfnr5zbbb"/></g><defs><clipPath id="healthiconsBNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:b-negative" {...props}></Icon>
