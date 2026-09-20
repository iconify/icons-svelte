<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuh2s1b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuh2s1b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:coin" {...props}></Icon>
