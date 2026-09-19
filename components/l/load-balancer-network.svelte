<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs6osbb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zs6osbb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:load-balancer-network" {...props}></Icon>
