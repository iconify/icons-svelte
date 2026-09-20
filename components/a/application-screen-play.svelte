<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_vll34og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_vll34og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:application-screen-play" {...props}></Icon>
