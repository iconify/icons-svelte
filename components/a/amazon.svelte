<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv5q-5cgz.css';
import '../../css/g/ga_k3d8mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zv5q-5cgz"/><path class="ga_k3d8mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:amazon" {...props}></Icon>
