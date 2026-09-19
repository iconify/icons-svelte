<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/runo8_caf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="runo8_caf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cloud-heavy-rain" {...props}></Icon>
