<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu1lzdgji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu1lzdgji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-2-ai-line" {...props}></Icon>
