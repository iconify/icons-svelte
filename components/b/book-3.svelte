<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bak2f201c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="bak2f201c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:book-3" {...props}></Icon>
