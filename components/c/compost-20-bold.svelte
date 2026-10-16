<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf_0_vbwb.css';
import '../../css/p/pxc5p1dyz.css';
import '../../css/n/ng4ifmbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xf_0_vbwb"/><path class="pxc5p1dyz"/><path class="ng4ifmbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:compost-20-bold" {...props}></Icon>
