<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5p5wfbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5p5wfbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-line-filled" {...props}></Icon>
