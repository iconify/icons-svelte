<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm2q0vrkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dm2q0vrkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-off-20-bold" {...props}></Icon>
