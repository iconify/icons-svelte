<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv3wvxecx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv3wvxecx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-1-line" {...props}></Icon>
