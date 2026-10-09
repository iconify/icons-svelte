<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbx5zccce.css';
import '../../css/h/ht2w2gbct.css';
import '../../css/i/ip_kbyb2f.css';
import '../../css/i/iqyfmrbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fbx5zccce"/><path class="ht2w2gbct"/><path class="ip_kbyb2f"/><path class="iqyfmrbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mvhr-20" {...props}></Icon>
