<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxhis1bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxhis1bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-2-fill" {...props}></Icon>
