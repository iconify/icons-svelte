<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlo6nbbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="rlo6nbbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:quote-close" {...props}></Icon>
