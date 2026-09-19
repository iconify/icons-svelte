<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc5a1e5us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc5a1e5us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-dots-2-filled" {...props}></Icon>
