<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8i7w_0jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8i7w_0jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-square-call-filled" {...props}></Icon>
