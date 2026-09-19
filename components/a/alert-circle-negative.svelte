<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/otpiyn0qj.css';
import '../../css/e/emq4-_fxk.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsAlertCircleNegative0)" class="cuyn6tgcc"><path class="otpiyn0qj"/><path clip-rule="evenodd" class="emq4-_fxk"/></g><defs><clipPath id="healthiconsAlertCircleNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:alert-circle-negative" {...props}></Icon>
