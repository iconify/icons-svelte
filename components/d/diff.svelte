<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulvg8qbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulvg8qbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:diff" {...props}></Icon>
