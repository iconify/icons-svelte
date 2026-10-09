<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4-gwpb0q.css';
import '../../css/o/o3015xv_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z4-gwpb0q"/><path class="o3015xv_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:interconnector-20-bold" {...props}></Icon>
