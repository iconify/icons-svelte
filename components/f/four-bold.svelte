<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmrqvr5kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jmrqvr5kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:four-bold" {...props}></Icon>
