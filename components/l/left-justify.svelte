<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyi-sxdur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="cyi-sxdur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:left-justify" {...props}></Icon>
