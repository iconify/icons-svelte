<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reu1yxf8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="reu1yxf8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-control-pad" {...props}></Icon>
