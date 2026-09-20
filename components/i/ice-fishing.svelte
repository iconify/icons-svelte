<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th9y1yc-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="th9y1yc-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:ice-fishing" {...props}></Icon>
