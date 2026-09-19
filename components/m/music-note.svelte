<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt5cytbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="pt5cytbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:music-note" {...props}></Icon>
