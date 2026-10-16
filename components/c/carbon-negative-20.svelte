<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcezpobhl.css';
import '../../css/m/m2oqjubvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hcezpobhl"/><path class="m2oqjubvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-negative-20" {...props}></Icon>
