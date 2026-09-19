<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw4l3nbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw4l3nbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-music" {...props}></Icon>
