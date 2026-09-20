<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrvfbr9fo.css';
import '../../css/r/r-62_47-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mrvfbr9fo"/><path class="r-62_47-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openmediavault" {...props}></Icon>
