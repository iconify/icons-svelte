<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2j8o9s_m.css';
import '../../css/n/n6kousbsq.css';
import '../../css/i/igillabjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n2j8o9s_m"/><path class="n6kousbsq"/><path class="igillabjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lawnmower-48-bold" {...props}></Icon>
