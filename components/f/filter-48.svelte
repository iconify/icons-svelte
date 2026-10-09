<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkwqbs4aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pkwqbs4aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:filter-48" {...props}></Icon>
