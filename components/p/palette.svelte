<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itj0e37iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="itj0e37iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:palette" {...props}></Icon>
