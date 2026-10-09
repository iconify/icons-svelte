<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmo-gj4um.css';
import '../../css/n/n-h74kx_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wmo-gj4um"/><path class="n-h74kx_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dishwasher-20-bold" {...props}></Icon>
