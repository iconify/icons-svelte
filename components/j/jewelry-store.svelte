<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv64nmb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="iv64nmb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:jewelry-store" {...props}></Icon>
