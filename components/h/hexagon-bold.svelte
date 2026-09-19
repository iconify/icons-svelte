<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwr4clbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cwr4clbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hexagon-bold" {...props}></Icon>
