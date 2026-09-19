<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asfiwqbnm.css';
import '../../css/l/l1y22fbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="asfiwqbnm"/><path class="l1y22fbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gitkraken-wordmark" {...props}></Icon>
