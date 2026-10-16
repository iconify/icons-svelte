<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdlgrw2ra.css';
import '../../css/o/o91sag11f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pdlgrw2ra"/><path class="o91sag11f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-full-48-bold" {...props}></Icon>
