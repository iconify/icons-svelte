<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4p3i9bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="k4p3i9bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:building-wheat" {...props}></Icon>
