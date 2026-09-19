<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/hsibv_iva.css';
import '../../css/d/dzsri3-lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="hsibv_iva"/><circle class="dzsri3-lf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:exclamation" {...props}></Icon>
