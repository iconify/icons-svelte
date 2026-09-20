<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5ari2byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="e5ari2byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:gas-station" {...props}></Icon>
