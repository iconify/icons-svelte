<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhs7z7x8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="lhs7z7x8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:low-vision-access" {...props}></Icon>
