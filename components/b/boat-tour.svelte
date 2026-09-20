<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivqjku9uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ivqjku9uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:boat-tour" {...props}></Icon>
