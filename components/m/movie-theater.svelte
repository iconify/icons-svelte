<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg3i-ab3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="lg3i-ab3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:movie-theater" {...props}></Icon>
