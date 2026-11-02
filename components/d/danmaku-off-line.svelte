<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2a1s-e8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2a1s-e8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-off-line" {...props}></Icon>
