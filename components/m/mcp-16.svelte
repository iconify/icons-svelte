<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v545msb3x.css';
import '../../css/i/izcv4zh7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v545msb3x"/><path class="izcv4zh7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mcp-16" {...props}></Icon>
