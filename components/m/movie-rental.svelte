<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_w102j1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="t_w102j1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:movie-rental" {...props}></Icon>
