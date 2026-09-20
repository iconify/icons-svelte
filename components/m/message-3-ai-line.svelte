<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gecrqn4vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gecrqn4vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-3-ai-line" {...props}></Icon>
