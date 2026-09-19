<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq4a1cc0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="rq4a1cc0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cherry" {...props}></Icon>
