<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmz7stm5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmz7stm5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cubes-stacked-solid" {...props}></Icon>
