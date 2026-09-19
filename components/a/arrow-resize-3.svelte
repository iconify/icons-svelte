<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xswgobbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xswgobbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-resize-3" {...props}></Icon>
