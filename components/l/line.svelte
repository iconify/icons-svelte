<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh475k0hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rh475k0hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:line" {...props}></Icon>
