<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww-nxl0ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ww-nxl0ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:manhole-drain" {...props}></Icon>
