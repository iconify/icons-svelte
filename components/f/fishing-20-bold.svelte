<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlu1ghlpb.css';
import '../../css/r/run42fbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mlu1ghlpb"/><path class="run42fbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fishing-20-bold" {...props}></Icon>
