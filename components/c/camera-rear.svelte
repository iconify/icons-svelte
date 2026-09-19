<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkvh0lmav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":512};
const content = `<path class="hkvh0lmav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:camera-rear" {...props}></Icon>
