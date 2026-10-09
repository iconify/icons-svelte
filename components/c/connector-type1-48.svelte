<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg-biwbzh.css';
import '../../css/n/nrf_j2jrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xg-biwbzh"/><path class="nrf_j2jrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-type1-48" {...props}></Icon>
