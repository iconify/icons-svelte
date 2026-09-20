<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylsm6d0zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylsm6d0zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-line" {...props}></Icon>
