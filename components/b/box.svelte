<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og8nmqhzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="og8nmqhzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:box" {...props}></Icon>
