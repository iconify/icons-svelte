<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slkapwbis.css';
import '../../css/t/tb36haboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="slkapwbis"/><path class="tb36haboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:milestone-48" {...props}></Icon>
