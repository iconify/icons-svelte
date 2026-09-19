<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi655acym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="fi655acym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-half-1" {...props}></Icon>
