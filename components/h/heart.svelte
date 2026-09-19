<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgb8txbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="pgb8txbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:heart" {...props}></Icon>
