<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhkq5mf7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="uhkq5mf7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:canoe" {...props}></Icon>
