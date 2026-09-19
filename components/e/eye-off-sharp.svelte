<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj5q7kbzd.css';
import '../../css/n/nabjh0sde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rj5q7kbzd"/><path class="nabjh0sde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:eye-off-sharp" {...props}></Icon>
