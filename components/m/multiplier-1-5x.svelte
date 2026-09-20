<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcruj4cal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcruj4cal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:multiplier-1-5x" {...props}></Icon>
