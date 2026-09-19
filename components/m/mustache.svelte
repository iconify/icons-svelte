<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdpuf55bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="cdpuf55bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:mustache" {...props}></Icon>
