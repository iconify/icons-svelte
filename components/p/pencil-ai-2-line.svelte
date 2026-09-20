<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_aahhbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_aahhbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pencil-ai-2-line" {...props}></Icon>
