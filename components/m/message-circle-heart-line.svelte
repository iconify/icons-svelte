<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_9zt_oer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_9zt_oer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-heart-line" {...props}></Icon>
