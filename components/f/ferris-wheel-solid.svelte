<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdads5mvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdads5mvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ferris-wheel-solid" {...props}></Icon>
