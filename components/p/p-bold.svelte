<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_k-j67ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="p_k-j67ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:p-bold" {...props}></Icon>
