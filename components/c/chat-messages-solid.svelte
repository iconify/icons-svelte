<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz2j1vbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz2j1vbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chat-messages-solid" {...props}></Icon>
