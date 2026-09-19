<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iplssnb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iplssnb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hockey-puck" {...props}></Icon>
