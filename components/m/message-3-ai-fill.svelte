<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8ed6kb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8ed6kb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-3-ai-fill" {...props}></Icon>
