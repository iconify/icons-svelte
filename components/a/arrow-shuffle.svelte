<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxx3h--im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="gxx3h--im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-shuffle" {...props}></Icon>
