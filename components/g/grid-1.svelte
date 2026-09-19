<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9o14pb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="p9o14pb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-1" {...props}></Icon>
