<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5dva-b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="t5dva-b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:link-1-bold" {...props}></Icon>
