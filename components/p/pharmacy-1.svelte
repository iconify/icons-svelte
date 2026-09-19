<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzprqip-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vzprqip-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pharmacy-1" {...props}></Icon>
