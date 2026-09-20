<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbqy7xyjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbqy7xyjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-bubble-outline" {...props}></Icon>
