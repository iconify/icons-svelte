<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfylp182e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="nfylp182e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:l-duo" {...props}></Icon>
