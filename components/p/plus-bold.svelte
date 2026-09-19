<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py_xqg_-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="py_xqg_-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plus-bold" {...props}></Icon>
