<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frp7i3eut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frp7i3eut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:message-ai-3-line" {...props}></Icon>
