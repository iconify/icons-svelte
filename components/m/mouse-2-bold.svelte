<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-o8fpw5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="b-o8fpw5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mouse-2-bold" {...props}></Icon>
