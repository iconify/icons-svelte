<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/t/th5jkovxy.css';
import '../../css/r/r-89_xbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="th5jkovxy"/><path class="r-89_xbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:location-outline" {...props}></Icon>
