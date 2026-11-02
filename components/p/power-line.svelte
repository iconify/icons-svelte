<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j38ouxb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j38ouxb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:power-line" {...props}></Icon>
