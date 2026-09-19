<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cskp9py_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cskp9py_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cross-christian" {...props}></Icon>
