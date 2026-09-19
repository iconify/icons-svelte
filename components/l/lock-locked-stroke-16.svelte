<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/a5zg-ob-o.css';
import '../../css/d/dcdwkgbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><rect class="a5zg-ob-o"/><path class="dcdwkgbts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lock-locked-stroke-16" {...props}></Icon>
