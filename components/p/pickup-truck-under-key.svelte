<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tptn74bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tptn74bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-under-key" {...props}></Icon>
