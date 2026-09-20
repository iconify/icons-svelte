<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5-fd1b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5-fd1b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-line-outline" {...props}></Icon>
