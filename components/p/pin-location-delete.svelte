<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty80_-i1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ty80_-i1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:pin-location-delete" {...props}></Icon>
