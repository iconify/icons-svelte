<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdiofmbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="gdiofmbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:castle" {...props}></Icon>
