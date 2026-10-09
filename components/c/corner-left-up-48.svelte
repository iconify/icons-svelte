<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-r-yzbxr.css';
import '../../css/u/u4q8h8_yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s-r-yzbxr"/><path class="u4q8h8_yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-left-up-48" {...props}></Icon>
