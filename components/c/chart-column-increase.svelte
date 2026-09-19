<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcgcscb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="mcgcscb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:chart-column-increase" {...props}></Icon>
