<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5ln8m42s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="l5ln8m42s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-lg" {...props}></Icon>
