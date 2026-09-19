<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1xiq3osc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="y1xiq3osc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cart-flatbed-suitcase" {...props}></Icon>
