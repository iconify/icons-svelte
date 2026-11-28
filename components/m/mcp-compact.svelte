<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7fxexb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p7fxexb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:mcp-compact" {...props}></Icon>
