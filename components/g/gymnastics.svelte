<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btx30rb9t.css';
import '../../css/i/ii8shdbmi.css';
import '../../css/r/rcg5y_bhj.css';
import '../../css/r/rddpr1bgn.css';
import '../../css/a/atk5wmbtu.css';
import '../../css/p/pa46_ab9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="btx30rb9t"><path class="ii8shdbmi"/><path class="rcg5y_bhj"/><path class="rddpr1bgn"/><path class="atk5wmbtu"/><path class="pa46_ab9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:gymnastics" {...props}></Icon>
