<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xndgo8bxx.css';
import '../../css/d/dj23tuv2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xndgo8bxx"/><path class="dj23tuv2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gnuradio-wordmark" {...props}></Icon>
