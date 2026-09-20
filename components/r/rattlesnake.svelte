<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmm2wi90d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pmm2wi90d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rattlesnake" {...props}></Icon>
