<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spu-vnbsz.css';
import '../../css/r/r4k-7obry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="spu-vnbsz"/><path class="r4k-7obry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:box-cutter-20-bold" {...props}></Icon>
