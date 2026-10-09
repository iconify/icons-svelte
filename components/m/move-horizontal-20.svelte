<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5zpafb6d.css';
import '../../css/y/y7i36sqce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w5zpafb6d"/><path class="y7i36sqce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-horizontal-20" {...props}></Icon>
