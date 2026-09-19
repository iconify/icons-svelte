<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2mrurzuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f2mrurzuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:excavator" {...props}></Icon>
