<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo2uy2bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jo2uy2bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:map-pin-slash" {...props}></Icon>
