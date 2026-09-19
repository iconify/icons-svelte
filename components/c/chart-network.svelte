<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa-vynbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pa-vynbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-network" {...props}></Icon>
