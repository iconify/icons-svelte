<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuqpfgb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuqpfgb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-bubble-1-filled" {...props}></Icon>
