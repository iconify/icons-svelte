<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv82_wb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mv82_wb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forklift-20-bold" {...props}></Icon>
