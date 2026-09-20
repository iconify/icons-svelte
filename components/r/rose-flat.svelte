<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yt10q1whe.css';
import '../../css/d/dg_3geblb.css';
import '../../css/e/e6y3v_b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yt10q1whe"/><path class="dg_3geblb"/><path class="e6y3v_b_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:rose-flat" {...props}></Icon>
