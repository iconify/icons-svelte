<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g3sa4vfqa.css';
import '../../css/d/djqgk_arv.css';
import '../../css/p/pqozpx_ba.css';
import '../../css/u/u9tt5cbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="g3sa4vfqa"/><path class="djqgk_arv"/><path class="pqozpx_ba"/><path class="u9tt5cbmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:close-policy-gaps" {...props}></Icon>
