<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_cx370op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_cx370op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-ai-3-fill" {...props}></Icon>
