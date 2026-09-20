<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ompyz3pxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ompyz3pxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:instructure-canvas" {...props}></Icon>
