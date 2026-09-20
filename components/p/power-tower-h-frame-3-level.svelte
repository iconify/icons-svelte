<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoz4v1svp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uoz4v1svp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-h-frame-3-level" {...props}></Icon>
