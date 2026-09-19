<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozby7f9jz.css';
import '../../css/p/px_2rvbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ozby7f9jz"/><path class="px_2rvbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:hourglass-outline" {...props}></Icon>
