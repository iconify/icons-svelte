<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvjwhfbog.css';
import '../../css/e/ef6a7mfgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rvjwhfbog"/><path class="ef6a7mfgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:outage-map-48" {...props}></Icon>
