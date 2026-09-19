<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9qalhbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j9qalhbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:pipe" {...props}></Icon>
