<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um1d8cbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="um1d8cbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:ampersand" {...props}></Icon>
