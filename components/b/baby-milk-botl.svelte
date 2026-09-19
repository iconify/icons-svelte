<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_1eaeb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="y_1eaeb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:baby-milk-botl" {...props}></Icon>
