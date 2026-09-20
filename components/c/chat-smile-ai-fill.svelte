<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu6_npblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu6_npblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-smile-ai-fill" {...props}></Icon>
