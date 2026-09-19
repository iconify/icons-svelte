<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8e6r52as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="y8e6r52as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:denojs-wordmark" {...props}></Icon>
