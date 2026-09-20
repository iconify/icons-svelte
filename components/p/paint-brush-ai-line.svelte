<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi1ootbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi1ootbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paint-brush-ai-line" {...props}></Icon>
