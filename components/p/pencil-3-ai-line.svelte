<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj06rnbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj06rnbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-3-ai-line" {...props}></Icon>
