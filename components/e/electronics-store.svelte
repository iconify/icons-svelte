<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heuf896sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="heuf896sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:electronics-store" {...props}></Icon>
