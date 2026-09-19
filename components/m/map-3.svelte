<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt0o8jbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="lt0o8jbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:map-3" {...props}></Icon>
