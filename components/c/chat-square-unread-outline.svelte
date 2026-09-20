<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooc0r-b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ooc0r-b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-unread-outline" {...props}></Icon>
