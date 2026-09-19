<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh066vywn.css';
import '../../css/c/cobkpuiyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh066vywn"/><path clip-rule="evenodd" class="cobkpuiyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:location-solid" {...props}></Icon>
