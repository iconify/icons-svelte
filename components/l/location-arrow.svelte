<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl5gjeb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tl5gjeb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:location-arrow" {...props}></Icon>
