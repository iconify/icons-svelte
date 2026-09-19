<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glpczdewo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="glpczdewo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-hearts-bold" {...props}></Icon>
