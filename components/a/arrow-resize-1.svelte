<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrr5k9-6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hrr5k9-6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-resize-1" {...props}></Icon>
