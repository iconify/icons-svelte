<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcr61ybai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcr61ybai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-off-line" {...props}></Icon>
