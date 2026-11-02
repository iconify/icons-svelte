<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziw9eiljc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziw9eiljc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paint-brush-ai-fill" {...props}></Icon>
