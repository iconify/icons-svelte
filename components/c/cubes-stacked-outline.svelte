<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra5zdu2wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra5zdu2wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cubes-stacked-outline" {...props}></Icon>
