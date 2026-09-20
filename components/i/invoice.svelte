<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfo2a7bug.css';
import '../../css/x/xnnzndbop.css';
import '../../css/h/hemw72bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rfo2a7bug"/><path class="xnnzndbop"/><path class="hemw72bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:invoice" {...props}></Icon>
