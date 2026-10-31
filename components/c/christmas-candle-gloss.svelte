<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltp05wb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltp05wb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:christmas-candle-gloss" {...props}></Icon>
