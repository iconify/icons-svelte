<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6gkppsme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6gkppsme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-round-unread" {...props}></Icon>
