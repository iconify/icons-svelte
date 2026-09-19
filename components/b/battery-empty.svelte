<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcov7on7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="vcov7on7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:battery-empty" {...props}></Icon>
