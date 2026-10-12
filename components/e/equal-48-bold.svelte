<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9hp2_byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e9hp2_byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:equal-48-bold" {...props}></Icon>
