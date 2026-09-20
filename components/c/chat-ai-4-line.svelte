<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyw2gnuap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyw2gnuap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-ai-4-line" {...props}></Icon>
