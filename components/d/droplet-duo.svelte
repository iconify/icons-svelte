<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgn7hvb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="mgn7hvb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:droplet-duo" {...props}></Icon>
