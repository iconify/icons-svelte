<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfv2d1nvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="yfv2d1nvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:general-contractor" {...props}></Icon>
