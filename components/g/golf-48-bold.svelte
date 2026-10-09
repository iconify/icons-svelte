<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxzo85ixz.css';
import '../../css/q/qyem97bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mxzo85ixz"/><path class="qyem97bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:golf-48-bold" {...props}></Icon>
