<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2i1ftbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="w2i1ftbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plane-arrival" {...props}></Icon>
