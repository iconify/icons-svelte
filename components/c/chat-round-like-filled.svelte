<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfse0xbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tfse0xbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-round-like-filled" {...props}></Icon>
