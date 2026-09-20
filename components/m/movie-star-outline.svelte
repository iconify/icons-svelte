<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylx6y-5zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylx6y-5zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-star-outline" {...props}></Icon>
