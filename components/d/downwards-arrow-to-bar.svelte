<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt-_m9ssp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lt-_m9ssp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:downwards-arrow-to-bar" {...props}></Icon>
