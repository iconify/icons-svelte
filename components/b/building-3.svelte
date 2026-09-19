<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7-l25bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="k7-l25bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:building-3" {...props}></Icon>
