<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2qct1-zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p2qct1-zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:import-failed" {...props}></Icon>
