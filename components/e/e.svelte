<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip9anpq2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ip9anpq2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:e" {...props}></Icon>
