<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tne_u8arr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="tne_u8arr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-thin-right" {...props}></Icon>
