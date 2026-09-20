<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np-n-1b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="np-n-1b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cancelled" {...props}></Icon>
