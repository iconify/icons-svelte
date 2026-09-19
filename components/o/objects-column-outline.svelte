<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub-8xvdrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub-8xvdrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:objects-column-outline" {...props}></Icon>
