<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3__alb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="m3__alb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:arxiv" {...props}></Icon>
