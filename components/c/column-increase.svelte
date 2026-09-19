<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slr3n6bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="slr3n6bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:column-increase" {...props}></Icon>
