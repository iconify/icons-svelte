<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed45f58pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ed45f58pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gnuradio-wordmark" {...props}></Icon>
