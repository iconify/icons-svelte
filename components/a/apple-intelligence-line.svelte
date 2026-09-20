<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsdri7q7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsdri7q7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:apple-intelligence-line" {...props}></Icon>
