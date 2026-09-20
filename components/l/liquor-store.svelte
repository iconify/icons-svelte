<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3vgmfb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="c3vgmfb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:liquor-store" {...props}></Icon>
