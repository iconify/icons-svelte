<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8sv8wb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8sv8wb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:frontdesk-ai-assistant-filled" {...props}></Icon>
