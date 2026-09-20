<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub30ixkmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub30ixkmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-4-ai-fill" {...props}></Icon>
