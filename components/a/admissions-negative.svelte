<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/fkkckfbrz.css';
import '../../css/z/zk0gytqrc.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsAdmissionsNegative0)" clip-rule="evenodd" class="n1lsf0bnc"><path class="fkkckfbrz"/><path class="zk0gytqrc"/></g><defs><clipPath id="healthiconsAdmissionsNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:admissions-negative" {...props}></Icon>
