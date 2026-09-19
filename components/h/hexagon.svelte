<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s75x9ebku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s75x9ebku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hexagon" {...props}></Icon>
