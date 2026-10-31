<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh8-obbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh8-obbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:reddit-fill-round" {...props}></Icon>
