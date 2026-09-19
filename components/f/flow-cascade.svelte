<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5zytllwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r5zytllwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:flow-cascade" {...props}></Icon>
