<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpel3hezc.css';
import '../../css/s/sqy8txize.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tpel3hezc"/><path class="sqy8txize"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-floor-48-bold" {...props}></Icon>
