<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy4ls9blv.css';
import '../../css/t/tihnfkx5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dy4ls9blv"/><path class="tihnfkx5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bungalow-20" {...props}></Icon>
