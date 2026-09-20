<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4ur9abjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4ur9abjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-1-ai-line" {...props}></Icon>
