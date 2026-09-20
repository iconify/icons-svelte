<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6oms7qjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6oms7qjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-unread-outline" {...props}></Icon>
