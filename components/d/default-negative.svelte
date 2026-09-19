<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m1vuaccwo.css';
import '../../css/c/cw0l96b5a.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsDefaultNegative0)" class="cuyn6tgcc"><path class="m1vuaccwo"/><path clip-rule="evenodd" class="cw0l96b5a"/></g><defs><clipPath id="healthiconsDefaultNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:default-negative" {...props}></Icon>
