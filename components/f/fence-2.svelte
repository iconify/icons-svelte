<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uio_1y2lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="uio_1y2lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:fence-2" {...props}></Icon>
