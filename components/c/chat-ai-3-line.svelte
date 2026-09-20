<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slhog6bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slhog6bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-ai-3-line" {...props}></Icon>
