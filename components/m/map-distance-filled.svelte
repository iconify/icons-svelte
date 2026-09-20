<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ljbbcsg.css';
import '../../css/m/mhbz-4bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ljbbcsg"/><path class="mhbz-4bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-distance-filled" {...props}></Icon>
