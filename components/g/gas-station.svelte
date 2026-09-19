<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjqoj_b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="zjqoj_b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:gas-station" {...props}></Icon>
