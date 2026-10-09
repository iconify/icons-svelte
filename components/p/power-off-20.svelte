<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dng7rgnyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dng7rgnyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-off-20" {...props}></Icon>
