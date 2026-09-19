<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsyyj6buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<rect transform="rotate(45 40 12)" class="dsyyj6buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:diamond-1-duo" {...props}></Icon>
