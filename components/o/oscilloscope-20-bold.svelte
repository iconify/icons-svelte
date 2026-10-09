<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgdmwwbvt.css';
import '../../css/j/jk8gvlbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rgdmwwbvt"/><path class="jk8gvlbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oscilloscope-20-bold" {...props}></Icon>
