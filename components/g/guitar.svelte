<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd9ow5bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="zd9ow5bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:guitar" {...props}></Icon>
