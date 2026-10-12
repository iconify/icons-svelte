<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st531kb5s.css';
import '../../css/e/etimskbbu.css';
import '../../css/r/rw1twdhke.css';
import '../../css/h/hp8bhknya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="st531kb5s"/><path class="etimskbbu"/><path class="rw1twdhke"/><path class="hp8bhknya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-station-48" {...props}></Icon>
