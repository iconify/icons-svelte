<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uklt71bum.css';
import '../../css/o/okvl3ohva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uklt71bum"/><path class="okvl3ohva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dry-cask-48" {...props}></Icon>
