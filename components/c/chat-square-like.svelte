<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j64rr6bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j64rr6bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-square-like" {...props}></Icon>
