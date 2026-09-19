<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9sz3i9ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p9sz3i9ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:regionalindicatorn" {...props}></Icon>
