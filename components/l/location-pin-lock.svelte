<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy7z0yolq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cy7z0yolq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:location-pin-lock" {...props}></Icon>
