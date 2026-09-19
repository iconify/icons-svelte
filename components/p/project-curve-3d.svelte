<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydgc67bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydgc67bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:project-curve-3d" {...props}></Icon>
