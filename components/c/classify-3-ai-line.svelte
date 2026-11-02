<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it_td9u6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it_td9u6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-3-ai-line" {...props}></Icon>
