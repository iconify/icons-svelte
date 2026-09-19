<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcgi76ztd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lcgi76ztd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:dna" {...props}></Icon>
