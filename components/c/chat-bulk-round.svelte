<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h06u_xbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h06u_xbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-bulk-round" {...props}></Icon>
