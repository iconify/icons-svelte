<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lazjyk96p.css';
import '../../css/z/z8apakboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lazjyk96p"/><path class="z8apakboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-arc-furnace-48" {...props}></Icon>
