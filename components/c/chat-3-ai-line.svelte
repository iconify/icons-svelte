<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5od25bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5od25bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-3-ai-line" {...props}></Icon>
