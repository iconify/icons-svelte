<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5zt3ccdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="w5zt3ccdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-speed-1-5x" {...props}></Icon>
