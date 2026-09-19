<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiako2bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="jiako2bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:brush-1" {...props}></Icon>
