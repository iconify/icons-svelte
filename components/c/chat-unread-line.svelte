<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrdrn2oqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrdrn2oqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-unread-line" {...props}></Icon>
