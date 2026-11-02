<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e604t8bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e604t8bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-2-ai-line" {...props}></Icon>
