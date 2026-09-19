<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew9ym6s6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ew9ym6s6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-circle-rycycle" {...props}></Icon>
