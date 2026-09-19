<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xq_8t15fs.css';
import '../../css/h/htn3cj9qd.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsCholeraNegative0)" class="cuyn6tgcc"><path class="xq_8t15fs"/><path clip-rule="evenodd" class="htn3cj9qd"/></g><defs><clipPath id="healthiconsCholeraNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cholera-negative" {...props}></Icon>
