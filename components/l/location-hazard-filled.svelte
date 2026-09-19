<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o88u_xb9d.css';
import '../../css/r/r7xl8ggtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o88u_xb9d"/><path class="r7xl8ggtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-hazard-filled" {...props}></Icon>
