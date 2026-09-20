<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb0la0xpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb0la0xpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-3-fill" {...props}></Icon>
