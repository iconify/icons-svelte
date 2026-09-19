<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pax50ybav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pax50ybav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:m" {...props}></Icon>
