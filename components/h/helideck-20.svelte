<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nygqmabbq.css';
import '../../css/i/iwdb11t7s.css';
import '../../css/l/l7sdbnbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nygqmabbq"/><path class="iwdb11t7s"/><path class="l7sdbnbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:helideck-20" {...props}></Icon>
