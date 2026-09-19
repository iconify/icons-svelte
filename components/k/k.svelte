<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpqs12bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xpqs12bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:k" {...props}></Icon>
