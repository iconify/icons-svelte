<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2bpp-u5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="h2bpp-u5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-resize-6" {...props}></Icon>
