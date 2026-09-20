<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad00tcuay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ad00tcuay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:home-outline" {...props}></Icon>
