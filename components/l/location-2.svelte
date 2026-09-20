<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfconw1ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yfconw1ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:location-2" {...props}></Icon>
