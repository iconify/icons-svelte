<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvhip5cnc.css';
import '../../css/e/e604b0bcg.css';
import '../../css/v/v6urtjbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kvhip5cnc"/><path class="e604b0bcg"/><path class="v6urtjbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:recloser-20" {...props}></Icon>
