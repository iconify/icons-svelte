<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw0lrnb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vw0lrnb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:analytics" {...props}></Icon>
