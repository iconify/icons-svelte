<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw3k0x4xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vw3k0x4xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:group" {...props}></Icon>
