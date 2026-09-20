<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klwawgbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="klwawgbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:arrow-left-outline" {...props}></Icon>
