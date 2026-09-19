<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8b32nb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="k8b32nb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-trend-down" {...props}></Icon>
