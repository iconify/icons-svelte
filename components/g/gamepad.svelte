<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7bil3o4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7bil3o4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gamepad" {...props}></Icon>
