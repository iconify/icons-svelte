<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbd53pbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="vbd53pbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:puzzle" {...props}></Icon>
