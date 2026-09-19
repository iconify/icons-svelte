<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v30e2vbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="v30e2vbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fahrenheit" {...props}></Icon>
