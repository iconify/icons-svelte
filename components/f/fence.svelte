<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4nf0t8ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="d4nf0t8ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:fence" {...props}></Icon>
