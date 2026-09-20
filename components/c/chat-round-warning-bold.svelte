<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynsh_1bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ynsh_1bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-warning-bold" {...props}></Icon>
