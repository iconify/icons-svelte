<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjnt2fbgz.css';
import '../../css/w/w8jjrpbxx.css';
import '../../css/h/h4pogicwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rjnt2fbgz"/><path class="w8jjrpbxx"/><path class="h4pogicwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:receipt-refund-20" {...props}></Icon>
