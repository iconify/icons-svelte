<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpuf8n8va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpuf8n8va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-dots" {...props}></Icon>
