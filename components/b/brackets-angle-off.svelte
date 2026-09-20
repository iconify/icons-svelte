<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2p1o2bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2p1o2bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:brackets-angle-off" {...props}></Icon>
