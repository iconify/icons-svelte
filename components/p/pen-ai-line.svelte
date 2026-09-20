<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3pylg09r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3pylg09r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-ai-line" {...props}></Icon>
