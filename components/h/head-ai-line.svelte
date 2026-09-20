<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tokhx3bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tokhx3bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:head-ai-line" {...props}></Icon>
