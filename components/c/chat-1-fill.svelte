<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpli6u5xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpli6u5xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-1-fill" {...props}></Icon>
