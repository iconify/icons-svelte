<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3za1pbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3za1pbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-conversation-circle-fill-round" {...props}></Icon>
