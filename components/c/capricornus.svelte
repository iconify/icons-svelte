<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/f/f_1rd_bme.css';
import '../../css/e/es56i3buc.css';
import '../../css/u/uc9bw1bea.css';
import '../../css/o/o613cobci.css';
import '../../css/y/y0ye5bc2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="f_1rd_bme"/><path class="es56i3buc"/><path class="uc9bw1bea"/><path class="o613cobci"/><circle class="y0ye5bc2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:capricornus" {...props}></Icon>
