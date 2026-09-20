<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxb6k-z4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxb6k-z4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-2-ai-line" {...props}></Icon>
