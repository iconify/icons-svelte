<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w456yoqax.css';
import '../../css/d/d_jwqly5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w456yoqax"/><path class="d_jwqly5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:phoenix-wordmark" {...props}></Icon>
