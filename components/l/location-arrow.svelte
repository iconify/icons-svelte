<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpn0pzs8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fpn0pzs8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:location-arrow" {...props}></Icon>
