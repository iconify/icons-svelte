<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpp_4zwkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpp_4zwkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-quote-fill" {...props}></Icon>
