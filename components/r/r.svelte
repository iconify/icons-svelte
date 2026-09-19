<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8y80gtls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x8y80gtls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:r" {...props}></Icon>
