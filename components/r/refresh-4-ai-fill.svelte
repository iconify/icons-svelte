<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_h4t5b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_h4t5b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-4-ai-fill" {...props}></Icon>
