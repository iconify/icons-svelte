<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgrk8c2ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgrk8c2ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:presentation-plus" {...props}></Icon>
