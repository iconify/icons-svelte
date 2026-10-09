<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psdyb3bve.css';
import '../../css/n/neg1e0pbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="psdyb3bve"/><path class="neg1e0pbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:airplay-48-bold" {...props}></Icon>
