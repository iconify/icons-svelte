<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czxxxcbar.css';
import '../../css/g/ga-ypktcu.css';
import '../../css/e/em6--xtxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="czxxxcbar"/><path class="ga-ypktcu"/><path class="em6--xtxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:airport-20-bold" {...props}></Icon>
