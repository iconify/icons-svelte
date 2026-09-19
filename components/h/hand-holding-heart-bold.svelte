<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrn3rpbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rrn3rpbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-holding-heart-bold" {...props}></Icon>
