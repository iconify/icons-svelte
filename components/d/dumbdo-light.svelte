<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmp48sblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bmp48sblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbdo-light" {...props}></Icon>
