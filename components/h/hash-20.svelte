<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq0_hgb3f.css';
import '../../css/v/vxl90jbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kq0_hgb3f"/><path class="vxl90jbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hash-20" {...props}></Icon>
