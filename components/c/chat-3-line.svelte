<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zczxv27do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zczxv27do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-3-line" {...props}></Icon>
