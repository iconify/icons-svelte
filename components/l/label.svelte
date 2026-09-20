<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xyjtgccot.css';
import '../../css/y/yv_ddbm3i.css';
import '../../css/l/lk771nbmv.css';
import '../../css/f/f1dvenbne.css';
import '../../css/e/earle6b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="xyjtgccot"><path class="yv_ddbm3i"/><path clip-rule="evenodd" class="lk771nbmv"/></g><path clip-rule="evenodd" class="f1dvenbne"/><path clip-rule="evenodd" class="earle6b1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:label" {...props}></Icon>
