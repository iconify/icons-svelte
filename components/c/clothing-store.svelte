<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo454jbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jo454jbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:clothing-store" {...props}></Icon>
