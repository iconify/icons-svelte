<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3q631rcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3q631rcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bed-round" {...props}></Icon>
