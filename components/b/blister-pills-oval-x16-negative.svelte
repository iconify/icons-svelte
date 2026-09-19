<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gwcwptb2r.css';
import '../../css/q/qit4vobxl.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsBlisterPillsOvalX16Negative0)" class="cuyn6tgcc"><path class="gwcwptb2r"/><path clip-rule="evenodd" class="qit4vobxl"/></g><defs><clipPath id="healthiconsBlisterPillsOvalX16Negative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blister-pills-oval-x16-negative" {...props}></Icon>
