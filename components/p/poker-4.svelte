<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwx6ummor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="dwx6ummor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:poker-4" {...props}></Icon>
