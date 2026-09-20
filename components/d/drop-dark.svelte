<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl-740brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rl-740brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:drop-dark" {...props}></Icon>
