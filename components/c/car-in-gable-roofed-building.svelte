<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mabj5bb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mabj5bb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-in-gable-roofed-building" {...props}></Icon>
