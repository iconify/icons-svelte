<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlx0ax7hq.css';
import '../../css/p/pgcgrcc8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mlx0ax7hq"/><path class="pgcgrcc8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cricket-20-bold" {...props}></Icon>
