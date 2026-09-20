<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w12155-xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w12155-xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openprinting-cups-light" {...props}></Icon>
