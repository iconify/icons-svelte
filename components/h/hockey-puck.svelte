<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-82anbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i-82anbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hockey-puck" {...props}></Icon>
