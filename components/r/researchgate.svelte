<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiiz1cyia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wiiz1cyia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:researchgate" {...props}></Icon>
