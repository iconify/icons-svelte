<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in3z5o4jq.css';
import '../../css/e/etos_bc7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="in3z5o4jq"/><path class="etos_bc7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:biome-wordmark" {...props}></Icon>
