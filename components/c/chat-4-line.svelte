<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iulz-f_yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iulz-f_yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-4-line" {...props}></Icon>
