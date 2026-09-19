<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjzd3-bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="xjzd3-bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:rocket" {...props}></Icon>
