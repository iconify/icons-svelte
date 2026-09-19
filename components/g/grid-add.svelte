<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c330qfbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="c330qfbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-add" {...props}></Icon>
