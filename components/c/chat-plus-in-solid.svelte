<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrje97bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lrje97bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chat-plus-in-solid" {...props}></Icon>
