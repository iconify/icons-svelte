<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1r-pxbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1r-pxbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:movie-ai-fill" {...props}></Icon>
