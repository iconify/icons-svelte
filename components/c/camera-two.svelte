<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dq65a4e6h.css';
import '../../css/v/v40rf1bhl.css';
import '../../css/b/bnsegsf1o.css';
import '../../css/l/l4y0xgwkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="dq65a4e6h"/><path class="v40rf1bhl"/><circle class="bnsegsf1o"/><circle class="l4y0xgwkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:camera-two" {...props}></Icon>
