<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqp4tdvik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqp4tdvik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-typing-outline" {...props}></Icon>
