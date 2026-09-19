<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg5j7ibl.css';
import '../../css/i/ipx9j1bxd.css';
import '../../css/k/k1e0ppbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="ipx9j1bxd"/><path class="k1e0ppbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:alert-circle-outline" {...props}></Icon>
