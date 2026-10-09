<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml5wo9g1f.css';
import '../../css/h/h3y6nxd1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ml5wo9g1f"/><path class="h3y6nxd1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-fire-20-bold" {...props}></Icon>
