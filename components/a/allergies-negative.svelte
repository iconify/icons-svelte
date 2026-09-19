<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vxaldzbwo.css';
import '../../css/b/bor6m379i.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsAllergiesNegative0)" clip-rule="evenodd" class="n1lsf0bnc"><path class="vxaldzbwo"/><path class="bor6m379i"/></g><defs><clipPath id="healthiconsAllergiesNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:allergies-negative" {...props}></Icon>
