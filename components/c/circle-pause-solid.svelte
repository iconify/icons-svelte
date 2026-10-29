<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0iy8x-ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0iy8x-ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-pause-solid" {...props}></Icon>
