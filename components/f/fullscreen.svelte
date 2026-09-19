<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y97f60bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y97f60bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:fullscreen" {...props}></Icon>
