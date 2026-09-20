<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs81imbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs81imbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-poll-line" {...props}></Icon>
