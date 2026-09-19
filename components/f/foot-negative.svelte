<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iuonsfbmk.css';
import '../../css/q/qgaeuqbmr.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsFootNegative0)" class="cuyn6tgcc"><path class="iuonsfbmk"/><path clip-rule="evenodd" class="qgaeuqbmr"/></g><defs><clipPath id="healthiconsFootNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:foot-negative" {...props}></Icon>
