<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rho2yp0gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="rho2yp0gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:book-store" {...props}></Icon>
