<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiw71x5na.css';
import '../../css/d/dvmj74bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jiw71x5na"/><path class="dvmj74bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dependabot" {...props}></Icon>
