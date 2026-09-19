<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x-y8j3bhz.css';
import '../../css/p/pnvm2wb6x.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsHospitalizedNegative0)" class="cuyn6tgcc"><path class="x-y8j3bhz"/><path clip-rule="evenodd" class="pnvm2wb6x"/></g><defs><clipPath id="healthiconsHospitalizedNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hospitalized-negative" {...props}></Icon>
