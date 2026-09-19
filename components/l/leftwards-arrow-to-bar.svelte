<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ors6v7rpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ors6v7rpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:leftwards-arrow-to-bar" {...props}></Icon>
