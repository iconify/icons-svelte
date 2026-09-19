<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1xb81bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="d1xb81bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:microphone-1-bold" {...props}></Icon>
