<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0boe6iuj.css';
import '../../css/w/wstn7hb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0boe6iuj"/><path class="wstn7hb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-unread-bold" {...props}></Icon>
