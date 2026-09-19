<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n0nx98bhb.css';
import '../../css/i/iihz_kbpm.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsEmergencyPostNegative0)" class="cuyn6tgcc"><path class="n0nx98bhb"/><path clip-rule="evenodd" class="iihz_kbpm"/></g><defs><clipPath id="healthiconsEmergencyPostNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:emergency-post-negative" {...props}></Icon>
