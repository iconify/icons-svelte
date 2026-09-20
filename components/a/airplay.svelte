<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz9_ijixv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz9_ijixv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:airplay" {...props}></Icon>
