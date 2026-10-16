<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5seiobvq.css';
import '../../css/u/uwrgjpbhp.css';
import '../../css/r/rs71wsbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r5seiobvq"/><path class="uwrgjpbhp"/><path class="rs71wsbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mobile-charger-20" {...props}></Icon>
