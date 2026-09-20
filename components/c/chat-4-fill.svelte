<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr_a0tb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr_a0tb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-4-fill" {...props}></Icon>
