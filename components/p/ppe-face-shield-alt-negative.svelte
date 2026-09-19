<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/thbf1-bfm.css';
import '../../css/i/ihgsnmbfr.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsPpeFaceShieldAltNegative0)" class="cuyn6tgcc"><path class="thbf1-bfm"/><path clip-rule="evenodd" class="ihgsnmbfr"/></g><defs><clipPath id="healthiconsPpeFaceShieldAltNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-face-shield-alt-negative" {...props}></Icon>
