<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvk5fntyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="bvk5fntyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cloud" {...props}></Icon>
