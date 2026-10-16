<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hei8_htdz.css';
import '../../css/m/m805q3b9o.css';
import '../../css/b/bhaor6bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="m805q3b9o"/><path class="bhaor6bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-substation-20-bold" {...props}></Icon>
