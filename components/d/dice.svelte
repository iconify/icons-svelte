<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5zec1bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y5zec1bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:dice" {...props}></Icon>
