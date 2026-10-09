<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2wnij_0h.css';
import '../../css/o/o6j5_ubif.css';
import '../../css/l/lu5ol8bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h2wnij_0h"/><path class="o6j5_ubif"/><path class="lu5ol8bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-48-bold" {...props}></Icon>
