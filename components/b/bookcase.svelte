<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p18b64bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="p18b64bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bookcase" {...props}></Icon>
