<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/occ8gwb-f.css';
import '../../css/j/jl4qfih3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="occ8gwb-f"/><path class="jl4qfih3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-arc-furnace-20" {...props}></Icon>
