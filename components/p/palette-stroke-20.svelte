<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5r0_vb_l.css';
import '../../css/b/bn7oupkej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t5r0_vb_l"/><path class="bn7oupkej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:palette-stroke-20" {...props}></Icon>
