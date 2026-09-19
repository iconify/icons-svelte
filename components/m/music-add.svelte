<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfkm__b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vfkm__b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:music-add" {...props}></Icon>
