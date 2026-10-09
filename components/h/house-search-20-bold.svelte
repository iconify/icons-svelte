<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmgp-hp4m.css';
import '../../css/r/rdst0hbya.css';
import '../../css/y/yulc80b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rmgp-hp4m"/><path class="rdst0hbya"/><path class="yulc80b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-search-20-bold" {...props}></Icon>
