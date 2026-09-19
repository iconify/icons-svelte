<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc3gbjbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fc3gbjbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:history" {...props}></Icon>
