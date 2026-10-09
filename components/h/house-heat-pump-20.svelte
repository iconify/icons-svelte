<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbx5zccce.css';
import '../../css/d/dclfrbcuw.css';
import '../../css/e/e9nmf_btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fbx5zccce"/><path class="dclfrbcuw"/><path class="e9nmf_btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-heat-pump-20" {...props}></Icon>
