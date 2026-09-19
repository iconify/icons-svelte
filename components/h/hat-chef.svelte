<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyfy9yb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="tyfy9yb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:hat-chef" {...props}></Icon>
