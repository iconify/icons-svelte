<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5_l8f-pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w5_l8f-pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:electric-cord-1" {...props}></Icon>
