<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x196-gi3w.css';
import '../../css/a/a04-1rvkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x196-gi3w"/><path class="a04-1rvkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:appcelerator-wordmark" {...props}></Icon>
