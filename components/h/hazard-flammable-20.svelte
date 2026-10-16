<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6_s1zkbf.css';
import '../../css/u/u_a85bcxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6_s1zkbf"/><path class="u_a85bcxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-flammable-20" {...props}></Icon>
