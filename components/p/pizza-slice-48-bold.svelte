<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayrrf_kwh.css';
import '../../css/n/nnu64c95v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ayrrf_kwh"/><path class="nnu64c95v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pizza-slice-48-bold" {...props}></Icon>
