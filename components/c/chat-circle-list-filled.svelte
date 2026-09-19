<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wekkzsr2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wekkzsr2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-list-filled" {...props}></Icon>
