<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t6v2fnbsv.css';
import '../../css/w/wll8irj0t.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthicons6Negative0)" class="cuyn6tgcc"><path class="t6v2fnbsv"/><path clip-rule="evenodd" class="wll8irj0t"/></g><defs><clipPath id="healthicons6Negative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:6-negative" {...props}></Icon>
