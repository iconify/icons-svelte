<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev4nrv7df.css';
import '../../css/d/dfad6bbbt.css';
import '../../css/a/axuha0b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ev4nrv7df"/><path class="dfad6bbbt"/><path class="axuha0b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:police-station-20" {...props}></Icon>
