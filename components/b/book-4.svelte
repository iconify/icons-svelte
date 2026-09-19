<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlhp9jokh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="hlhp9jokh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:book-4" {...props}></Icon>
