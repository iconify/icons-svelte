<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5bsgabgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="i5bsgabgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bezier-hexagon" {...props}></Icon>
