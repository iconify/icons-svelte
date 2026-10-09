<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny-w6qbwa.css';
import '../../css/p/pv7m710be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ny-w6qbwa"/><path class="pv7m710be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emissions-report-20-bold" {...props}></Icon>
