<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_bz0t0lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z_bz0t0lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-bar-overlay" {...props}></Icon>
