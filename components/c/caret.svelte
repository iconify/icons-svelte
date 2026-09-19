<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry3wv0bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ry3wv0bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:caret" {...props}></Icon>
