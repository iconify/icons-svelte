<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm8gc9syk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm8gc9syk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-bubble" {...props}></Icon>
