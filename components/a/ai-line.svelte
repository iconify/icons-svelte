<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_j775vwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_j775vwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ai-line" {...props}></Icon>
