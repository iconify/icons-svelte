<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0t5pub1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="w0t5pub1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-left" {...props}></Icon>
