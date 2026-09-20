<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuj5j5b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuj5j5b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-x-circle" {...props}></Icon>
