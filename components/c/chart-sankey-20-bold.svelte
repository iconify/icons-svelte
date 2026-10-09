<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogowslhhc.css';
import '../../css/d/dnvyigb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ogowslhhc"/><path class="dnvyigb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-sankey-20-bold" {...props}></Icon>
