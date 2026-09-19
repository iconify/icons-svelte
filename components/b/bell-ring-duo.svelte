<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lquxq_0-b.css';
import '../../css/e/eh_m-vi9v.css';
import '../../css/c/comdxum3w.css';
import '../../css/k/kye1psbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lquxq_0-b"/><path class="eh_m-vi9v"/><path class="comdxum3w"/><path class="kye1psbcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-ring-duo" {...props}></Icon>
