<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h10k0p92q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h10k0p92q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-3-ai-line" {...props}></Icon>
