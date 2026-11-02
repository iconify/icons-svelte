<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1wsflb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1wsflb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paint-brush-ai-line" {...props}></Icon>
