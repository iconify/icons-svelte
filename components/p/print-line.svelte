<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_x0k4bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_x0k4bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:print-line" {...props}></Icon>
