<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpr4c1bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="lpr4c1bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:like" {...props}></Icon>
