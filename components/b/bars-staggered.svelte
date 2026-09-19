<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw0emjb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gw0emjb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bars-staggered" {...props}></Icon>
