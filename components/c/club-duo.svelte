<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0x3vwutg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="j0x3vwutg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:club-duo" {...props}></Icon>
