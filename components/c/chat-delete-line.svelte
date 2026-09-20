<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnr8hacgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnr8hacgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-delete-line" {...props}></Icon>
