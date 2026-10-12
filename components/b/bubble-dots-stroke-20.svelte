<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aui9c_vuc.css';
import '../../css/b/bmmy7ztjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aui9c_vuc"/><path class="bmmy7ztjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubble-dots-stroke-20" {...props}></Icon>
