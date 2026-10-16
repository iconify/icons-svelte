<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdlgrw2ra.css';
import '../../css/x/x-e0pwbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pdlgrw2ra"/><path class="x-e0pwbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-half-48-bold" {...props}></Icon>
