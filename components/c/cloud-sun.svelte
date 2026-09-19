<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f80hj5bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="f80hj5bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cloud-sun" {...props}></Icon>
