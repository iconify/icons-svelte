<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc9kp8bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xc9kp8bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:plotly-wordmark" {...props}></Icon>
