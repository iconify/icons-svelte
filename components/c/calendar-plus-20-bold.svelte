<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7qx85bwi.css';
import '../../css/n/nrnabgmon.css';
import '../../css/l/lfyak8xiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g7qx85bwi"/><path class="nrnabgmon"/><path class="lfyak8xiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-plus-20-bold" {...props}></Icon>
