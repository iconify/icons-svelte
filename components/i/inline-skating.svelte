<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvdmlcc9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="gvdmlcc9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:inline-skating" {...props}></Icon>
