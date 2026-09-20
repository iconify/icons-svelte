<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvdl01b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zvdl01b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bell-in-tall-gable-roofed-building" {...props}></Icon>
