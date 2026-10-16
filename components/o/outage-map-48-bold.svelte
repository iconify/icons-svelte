<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9jxscckh.css';
import '../../css/r/r83j7_bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r9jxscckh"/><path class="r83j7_bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:outage-map-48-bold" {...props}></Icon>
