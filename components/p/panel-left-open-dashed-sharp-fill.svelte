<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/hwv8c50wu.css';
import '../../css/d/dwlz50b1l.css';
import '../../css/h/h5zq5sxkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hwv8c50wu"/><path class="dwlz50b1l"/><path class="h5zq5sxkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-left-open-dashed-sharp-fill" {...props}></Icon>
