<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/m060p1bup.css';
import '../../css/l/lzd54cadi.css';
import '../../css/h/h5zq5sxkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m060p1bup"/><path class="lzd54cadi"/><path class="h5zq5sxkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-left-open-dashed-sharp-two-tone" {...props}></Icon>
