<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv-waabpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv-waabpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-g-clef" {...props}></Icon>
