<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch7d5hy0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ch7d5hy0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:newspaper" {...props}></Icon>
