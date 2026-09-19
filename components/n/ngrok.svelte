<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cap41rbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cap41rbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ngrok" {...props}></Icon>
