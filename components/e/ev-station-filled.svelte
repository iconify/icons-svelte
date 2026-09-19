<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy6ubfbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy6ubfbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ev-station-filled" {...props}></Icon>
