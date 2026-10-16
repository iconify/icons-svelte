<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdlgrw2ra.css';
import '../../css/s/skmrpcbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pdlgrw2ra"/><path class="skmrpcbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-crescent-48-bold" {...props}></Icon>
