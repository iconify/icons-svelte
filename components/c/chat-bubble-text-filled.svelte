<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e84xm75-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e84xm75-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-bubble-text-filled" {...props}></Icon>
