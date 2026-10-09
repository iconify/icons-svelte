<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-50ztbgo.css';
import '../../css/z/zof54ffpy.css';
import '../../css/i/ibk_3obac.css';
import '../../css/u/us_48ubxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r-50ztbgo"/><path class="zof54ffpy"/><path class="ibk_3obac"/><path class="us_48ubxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cold-storage-48-bold" {...props}></Icon>
