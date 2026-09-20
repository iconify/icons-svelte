<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u86v46blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u86v46blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cellular-network-lte" {...props}></Icon>
