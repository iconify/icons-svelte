<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rle9alb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rle9alb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-card-fill" {...props}></Icon>
