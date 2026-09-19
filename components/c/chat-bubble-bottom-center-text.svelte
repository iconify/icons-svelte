<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-kp13e4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-kp13e4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-bottom-center-text" {...props}></Icon>
