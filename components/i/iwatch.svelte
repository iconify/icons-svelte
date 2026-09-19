<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/d/d18fr-b_e.css';
import '../../css/j/j7-vsc_mc.css';
import '../../css/d/dw5jrb3yq.css';
import '../../css/f/fp4xfkbkn.css';
import '../../css/z/zx06p67jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="d18fr-b_e"/><path class="j7-vsc_mc"/><path class="dw5jrb3yq"/><path class="fp4xfkbkn"/><path class="zx06p67jt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:iwatch" {...props}></Icon>
