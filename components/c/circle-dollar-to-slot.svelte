<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_r80-udu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k_r80-udu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-dollar-to-slot" {...props}></Icon>
