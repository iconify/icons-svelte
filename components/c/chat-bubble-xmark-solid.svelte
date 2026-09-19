<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucu-4jbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ucu-4jbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chat-bubble-xmark-solid" {...props}></Icon>
