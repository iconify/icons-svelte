<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4o9b8mlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w4o9b8mlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:dog" {...props}></Icon>
