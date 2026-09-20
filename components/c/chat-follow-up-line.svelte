<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if-ttfbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if-ttfbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-follow-up-line" {...props}></Icon>
