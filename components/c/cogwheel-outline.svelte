<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkvmf2k6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jkvmf2k6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cogwheel-outline" {...props}></Icon>
