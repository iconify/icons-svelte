<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze9mvuf9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ze9mvuf9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:can-water" {...props}></Icon>
