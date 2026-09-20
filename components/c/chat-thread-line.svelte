<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk_5bov8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk_5bov8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-thread-line" {...props}></Icon>
