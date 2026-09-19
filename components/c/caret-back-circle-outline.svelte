<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkkwb243e.css';
import '../../css/l/lsg5j7ibl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkkwb243e"/><path class="lsg5j7ibl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:caret-back-circle-outline" {...props}></Icon>
