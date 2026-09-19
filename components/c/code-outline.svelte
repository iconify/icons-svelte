<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j72wdcj5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="j72wdcj5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:code-outline" {...props}></Icon>
