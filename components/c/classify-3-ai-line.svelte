<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwg-msb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwg-msb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-3-ai-line" {...props}></Icon>
