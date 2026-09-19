<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iulq5fb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="iulq5fb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mouse-pointer" {...props}></Icon>
