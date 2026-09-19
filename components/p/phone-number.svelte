<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re149_bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="re149_bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:phone-number" {...props}></Icon>
