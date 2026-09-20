<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adh2_0ble.css';
import '../../css/y/y0igkftrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="adh2_0ble"/><path class="y0igkftrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:right-arrow-curving-left" {...props}></Icon>
