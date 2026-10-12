<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v19yd0bwi.css';
import '../../css/k/khpnrke8g.css';
import '../../css/k/kz95gib1r.css';
import '../../css/d/dsqatabik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v19yd0bwi"/><path class="khpnrke8g"/><path class="kz95gib1r"/><path class="dsqatabik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drill-press-20-bold" {...props}></Icon>
