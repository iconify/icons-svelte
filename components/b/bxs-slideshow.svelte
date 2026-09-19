<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjtri3beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjtri3beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-slideshow" {...props}></Icon>
