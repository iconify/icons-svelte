<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkv56e61f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="zkv56e61f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:jump-forward" {...props}></Icon>
