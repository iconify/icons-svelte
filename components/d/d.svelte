<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri3dx_bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ri3dx_bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:d" {...props}></Icon>
