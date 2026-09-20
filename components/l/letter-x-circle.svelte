<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvhn4lvcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvhn4lvcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-x-circle" {...props}></Icon>
