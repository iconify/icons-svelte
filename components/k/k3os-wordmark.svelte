<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut-71fb_j.css';
import '../../css/n/nlgbk_b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ut-71fb_j"/><path class="nlgbk_b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:k3os-wordmark" {...props}></Icon>
