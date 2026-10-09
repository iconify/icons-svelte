<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyn_k2bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dyn_k2bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pause-20-bold" {...props}></Icon>
