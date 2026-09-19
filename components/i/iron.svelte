<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdauo9bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="jdauo9bfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:iron" {...props}></Icon>
