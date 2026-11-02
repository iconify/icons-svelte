<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1qi6g_cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1qi6g_cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baseball-line" {...props}></Icon>
