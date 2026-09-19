<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf6m7r4pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jf6m7r4pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:magnifying-glass-chart" {...props}></Icon>
