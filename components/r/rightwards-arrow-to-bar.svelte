<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aopzmf17w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="aopzmf17w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:rightwards-arrow-to-bar" {...props}></Icon>
