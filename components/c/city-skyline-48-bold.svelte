<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw5ycab-f.css';
import '../../css/o/otkch_brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uw5ycab-f"/><path class="otkch_brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:city-skyline-48-bold" {...props}></Icon>
