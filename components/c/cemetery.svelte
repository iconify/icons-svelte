<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm0rmt9ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="fm0rmt9ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:cemetery" {...props}></Icon>
