<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r61ucs0yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="r61ucs0yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-drashed" {...props}></Icon>
