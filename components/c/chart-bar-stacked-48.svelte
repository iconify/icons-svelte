<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c65-ehvfy.css';
import '../../css/s/s5l58c2dr.css';
import '../../css/d/d0had8aoi.css';
import '../../css/z/z1c3c8wmj.css';
import '../../css/m/mn2t0b19e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c65-ehvfy"/><path class="s5l58c2dr"/><path class="d0had8aoi"/><path class="z1c3c8wmj"/><path class="mn2t0b19e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-bar-stacked-48" {...props}></Icon>
