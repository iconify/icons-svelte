<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylvg4v1fy.css';
import '../../css/h/hsx1pzxph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ylvg4v1fy"/><path class="hsx1pzxph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:real-estate-building-4" {...props}></Icon>
