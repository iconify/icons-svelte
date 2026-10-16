<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxj2d1b_f.css';
import '../../css/n/nmhn6wb1y.css';
import '../../css/y/ycfhepb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fxj2d1b_f"/><path class="nmhn6wb1y"/><path class="ycfhepb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-tree-20-bold" {...props}></Icon>
