<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gro8lebrz.css';
import '../../css/w/w05qs9b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gro8lebrz"/><path class="w05qs9b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:loft-insulation-20-bold" {...props}></Icon>
