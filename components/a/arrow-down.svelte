<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zig2q4ohe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="zig2q4ohe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-down" {...props}></Icon>
