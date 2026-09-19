<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqndebbwd.css';
import '../../css/d/d3236htcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqndebbwd"/><path class="d3236htcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bonfire-sharp" {...props}></Icon>
