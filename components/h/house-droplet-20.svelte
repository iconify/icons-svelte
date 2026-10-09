<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbx5zccce.css';
import '../../css/b/bq0mgxbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fbx5zccce"/><path class="bq0mgxbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-droplet-20" {...props}></Icon>
