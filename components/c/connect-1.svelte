<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfj60beug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="tfj60beug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:connect-1" {...props}></Icon>
