<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4493zr5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="x4493zr5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:color-picker" {...props}></Icon>
