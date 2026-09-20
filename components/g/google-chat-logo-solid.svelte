<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6zsf5bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s6zsf5bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-chat-logo-solid" {...props}></Icon>
