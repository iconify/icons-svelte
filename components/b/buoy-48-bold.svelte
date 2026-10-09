<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p83hrs6_m.css';
import '../../css/z/zy1--_bqv.css';
import '../../css/e/ewz0dq5ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p83hrs6_m"/><path class="zy1--_bqv"/><path class="ewz0dq5ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:buoy-48-bold" {...props}></Icon>
