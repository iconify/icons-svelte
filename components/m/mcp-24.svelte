<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz4uhub5s.css';
import '../../css/l/l8wwf1bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz4uhub5s"/><path class="l8wwf1bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mcp-24" {...props}></Icon>
