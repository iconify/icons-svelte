<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pore5-dgs.css';
import '../../css/r/r6ewlybsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pore5-dgs"/><path class="r6ewlybsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frame-20-bold" {...props}></Icon>
