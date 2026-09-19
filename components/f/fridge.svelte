<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a17-j_b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="a17-j_b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:fridge" {...props}></Icon>
