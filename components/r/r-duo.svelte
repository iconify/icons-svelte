<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn6pd7b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tn6pd7b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:r-duo" {...props}></Icon>
