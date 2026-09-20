<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg2686ecp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg2686ecp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-bar-to-right-dashed" {...props}></Icon>
