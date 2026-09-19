<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvw6ur04b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="rvw6ur04b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:line-two-angle-point" {...props}></Icon>
