<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzxt0mswz.css';
import '../../css/h/htyx_ybsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hzxt0mswz"/><path class="htyx_ybsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-compressor-48-bold" {...props}></Icon>
