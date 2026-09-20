<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbcw621xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cbcw621xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-dark" {...props}></Icon>
