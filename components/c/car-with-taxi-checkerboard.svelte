<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw9-n0btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vw9-n0btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-taxi-checkerboard" {...props}></Icon>
