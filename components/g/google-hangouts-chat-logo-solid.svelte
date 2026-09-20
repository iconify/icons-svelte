<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhhug9b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rhhug9b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-hangouts-chat-logo-solid" {...props}></Icon>
