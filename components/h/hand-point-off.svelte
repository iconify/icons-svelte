<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xyjtgccot.css';
import '../../css/c/ck3rq6bkb.css';
import '../../css/c/c63o3wabg.css';
import '../../css/x/x6e3mnbvk.css';
import '../../css/s/st8r_y1jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><g class="xyjtgccot"><path class="ck3rq6bkb"/><path class="c63o3wabg"/></g><path clip-rule="evenodd" class="x6e3mnbvk"/><path class="st8r_y1jl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:hand-point-off" {...props}></Icon>
