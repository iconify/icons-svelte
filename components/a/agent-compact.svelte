<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztoxc1bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ztoxc1bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:agent-compact" {...props}></Icon>
