<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2f6fwbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="n2f6fwbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:hair-care" {...props}></Icon>
