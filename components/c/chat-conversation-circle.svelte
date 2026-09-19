<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixlzqjbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixlzqjbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chat-conversation-circle" {...props}></Icon>
