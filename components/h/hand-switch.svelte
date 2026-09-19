<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow7ny9x4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="ow7ny9x4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:hand-switch" {...props}></Icon>
