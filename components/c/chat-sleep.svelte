<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l56c42bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l56c42bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-sleep" {...props}></Icon>
