<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9ogdpbce.css';
import '../../css/d/dhiwzmb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d9ogdpbce"/><path class="dhiwzmb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nuclear-plant-20" {...props}></Icon>
