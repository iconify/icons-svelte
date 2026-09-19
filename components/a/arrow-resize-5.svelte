<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnpdkbc0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="jnpdkbc0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-resize-5" {...props}></Icon>
