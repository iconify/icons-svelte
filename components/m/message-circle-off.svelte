<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw4l773-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw4l773-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-circle-off" {...props}></Icon>
