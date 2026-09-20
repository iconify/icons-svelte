<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycgn9rbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycgn9rbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:remove-box" {...props}></Icon>
