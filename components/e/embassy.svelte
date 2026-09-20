<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3byvac3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="e3byvac3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:embassy" {...props}></Icon>
