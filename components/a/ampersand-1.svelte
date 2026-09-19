<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjvk998zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rjvk998zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:ampersand-1" {...props}></Icon>
