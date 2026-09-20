<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3bapxb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3bapxb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-3-fill" {...props}></Icon>
