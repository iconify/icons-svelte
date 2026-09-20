<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6khetxdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x6khetxdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-map-pin-with-dot" {...props}></Icon>
