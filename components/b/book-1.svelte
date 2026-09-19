<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm3w0vbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hm3w0vbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:book-1" {...props}></Icon>
