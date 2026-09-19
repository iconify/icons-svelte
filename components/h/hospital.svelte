<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8a-ns-2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="u8a-ns-2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:hospital" {...props}></Icon>
