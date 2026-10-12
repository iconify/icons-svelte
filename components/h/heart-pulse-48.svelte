<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvnfjofcq.css';
import '../../css/e/e2jvog8gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vvnfjofcq"/><path class="e2jvog8gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-pulse-48" {...props}></Icon>
