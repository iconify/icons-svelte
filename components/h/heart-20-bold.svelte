<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp3hv2d4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yp3hv2d4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-20-bold" {...props}></Icon>
