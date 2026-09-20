<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfrgf7bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfrgf7bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cyberchef-light" {...props}></Icon>
