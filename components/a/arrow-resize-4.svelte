<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdit7nflt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fdit7nflt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-resize-4" {...props}></Icon>
