<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n885a6bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n885a6bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-error-filled" {...props}></Icon>
