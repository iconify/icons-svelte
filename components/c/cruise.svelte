<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy9uw-bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dy9uw-bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cruise" {...props}></Icon>
