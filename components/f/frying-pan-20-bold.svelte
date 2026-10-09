<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6_3zpu9x.css';
import '../../css/p/p6okrgv2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s6_3zpu9x"/><path class="p6okrgv2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frying-pan-20-bold" {...props}></Icon>
