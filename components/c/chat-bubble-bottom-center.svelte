<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7vq71bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7vq71bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-bottom-center" {...props}></Icon>
