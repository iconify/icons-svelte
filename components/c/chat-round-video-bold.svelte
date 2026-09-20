<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjqu2ujmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gjqu2ujmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-video-bold" {...props}></Icon>
