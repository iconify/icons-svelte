<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qid4wwbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qid4wwbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chat-minus-in-solid" {...props}></Icon>
