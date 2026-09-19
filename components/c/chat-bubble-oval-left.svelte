<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5-q7tbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5-q7tbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-oval-left" {...props}></Icon>
