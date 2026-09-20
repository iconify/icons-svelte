<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh5krp3xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hh5krp3xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-under-wrench" {...props}></Icon>
