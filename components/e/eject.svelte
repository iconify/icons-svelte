<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hawr1bc8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="hawr1bc8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:eject" {...props}></Icon>
