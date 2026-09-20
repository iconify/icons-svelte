<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsaue0b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsaue0b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-bold" {...props}></Icon>
