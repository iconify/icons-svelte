<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pczyoks0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="pczyoks0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:gear" {...props}></Icon>
