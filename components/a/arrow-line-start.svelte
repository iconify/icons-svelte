<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5c_1dupa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="j5c_1dupa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-line-start" {...props}></Icon>
